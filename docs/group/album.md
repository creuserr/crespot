<h3 align="center"><code>Album</code> <kbd>Object</kbd></h3>

An `Album` object contains 12 properties (excluding `_market` and `_token`). For the snippet class, please refer to [`AlbumSnippet`](https://github.com/creuserr/crespot/tree/main/docs/snippet/album.md).

### `str: id`
This is the ID of the album.

### `str: label`
This is the label name of the album.

### `str: type`
This is the album type. It can be an `single`, `album`, or `compilation`.

### `str: external`
This is the album's page url of Spotify's website.

### `int: popularity`
This is the popularity score of the album.

### `int: total`
This is the total amount of tracks in the albums.

### `str: name`
This is the name of the album.

### `str: date`
This is the first release date of the album. The format is `yyyy-mm-dd`.

### `list(str): markets` <kbd>Undefinable</kbd>
This is the list of available markets of the album.

### `list(ArtistSnippet): artists`
This is a list of snippet artists of the album.

### `list(TrackSnippet): tracks`
This is a list of snippet tracks of the album.

### `list(Image): images`
This is the artwork images of the album.

### Related links

- [`ArtistSnippet`](https://github.com/creuserr/crespot/tree/main/docs/snippet/artist.md)
- [`TrackSnippet`](https://github.com/creuserr/crespot/tree/main/docs/snippet/track.md)
- [`Image`](https://github.com/creuserr/crespot/tree/main/docs/detail/image.md)

<img src="https://komarev.com/ghpvc/?username=creuserr" alt="" width="0"></img>
