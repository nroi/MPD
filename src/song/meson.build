song = static_library(
  'song',
  'DetachedSong.cxx',
  'Escape.cxx',
  'StringFilter.cxx',
  'UriSongFilter.cxx',
  'BaseSongFilter.cxx',
  'TagSongFilter.cxx',
  'ModifiedSinceSongFilter.cxx',
  'AudioFormatSongFilter.cxx',
  'AndSongFilter.cxx',
  'OptimizeFilter.cxx',
  'Filter.cxx',
  'LightSong.cxx',
  include_directories: inc,
)

song_dep = declare_dependency(
  link_with: song,
  dependencies: [
    icu_dep,
    tag_dep,
    util_dep,
  ],
)
