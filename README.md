# Google Play Review Demo Media

This public repository is a synthetic test catalog created for software testing and Google Play application review.

## Reviewer playlist

`https://raw.githubusercontent.com/fahrettinaslan66/google-play-review-demo/main/playlist.m3u`

The playlist contains:
- 2 Live TV demo channels, each with a synthetic channel logo
- 3 Movies with a synthetic poster
- 2 Series (Horizon and Nova Files) with season/episode naming and a synthetic poster
- 5 Series episodes in total
- XMLTV EPG metadata for the Live TV section

The M3U uses explicit `group-title="Live TV"`, `group-title="Movies"`, and `group-title="Series"` values. Movie and series items include `tvg-logo` poster URLs. Series items also include `series-name`, `season-number`, and `episode-number` metadata so compatible parsers can group episodes.

All media, artwork and metadata are synthetic test content. No third-party broadcaster streams, film/series clips, copyrighted posters, logos or music are included.

See `RIGHTS.md` for the review-use rights statement.
