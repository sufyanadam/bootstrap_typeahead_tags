# Bootstrap-Typeahead

Modification of Bootstrap Typeahead for Bottle.io.

## Enhancements

 - Hashtags support

## Usage

### Hashtags support

    $('#entry-submit').typeahead({
      source: tags,
      useTags: true,
      symbol: "#"       # Define hashtag symbol, by default '#'
    });

*Warning*: setting `useTags` to true, will exclusively work with tags.

