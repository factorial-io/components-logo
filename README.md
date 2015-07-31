# Factorial.io components: Logo

A Factorial.io component to display a logo with configurable source, height and ratio.

## Configuration

The array the component needs looks like this:
```php
$data = array(
  'src' => 'Url://to-your.image',
  'title' => 'Your Logo Title'
);

// Optional
$options = array(
   'width' => '1em',
  'height' => '32px',
};

```

### Data

* `src`: the image-url.
* `title`: the text in the invisable span for screenreader

### Options

* `ratio`: the ratio of the logo in `em`
* `height`: the height of the logo in `px` or `em`

## Usage

If you want to include the component in one of your template-files, just use

php
```php
  print component('factorial-io-components-logo', $data, $options));
```
haml
```php
  = component('factorial-io-components-logo', $data, $options)
```
To use the fixture-data of the component for testing, etc, use

```php
  print compontent(‘factorial-io-components-logo’, NULL, $options)
  // or
  print compontent(‘factorial-io-components-logo’)
```

