<h3 align="center"><code>Show</code> <kbd>Object</kbd></h3>

A `Show` object contains 12 properties (excluding `_market` and `_token`). For the snippet class, please refer to [`ShowSnippet`](https://github.com/creuserr/crespot/tree/main/docs/snippet/show.md).

### `str: id`
This is the ID of the show.

### `str: description` <kbd>Nullable</kbd>
This is the description of the show.

### `str: html_description` <kbd>Nullable</kbd>
This is the HTML-formatted description of the show.

### `str: external`
This is the show's page url of Spotify's website.

### `list(Copyright): copyrights`
This is a list of copyright informations of the show.

### `list(str): markets` <kbd>Undefinable</kbd>
This is the list of available markets of the show.

### `str: name`
This is the name of the show.

### `int: total`
This is the total amount of episodes in the show.

### `str: type`
This is the media type of the show.

### `str: publisher`
This is the publisher of the show.

### `list(EpisodeSnippet): episodes`
This is a list of snippet episodes of the show.

### `list(Image): images`
This is the artwork images of the playlist.

### Related links

- [`Copyright`](https://github.com/creuserr/crespot/tree/main/docs/detail/copyright.md)
- [`EpisodeSnippet`](https://github.com/creuserr/crespot/tree/main/docs/snippet/episode.md)
- [`Image`](https://github.com/creuserr/crespot/tree/main/docs/detail/image.md)

<img src="https://komarev.com/ghpvc/?username=creuserr" alt="" width="0"></img>
