# Factorial.io components: Logo

A Factorial.io component to display a logo with configurable source, height and ratio.

## Configuration

The array the component needs looks like this:
```php
$your_array = array(
  'src' => 'Url://to-your.image',
  'width' => '1em',
  'height' => '32px',
  'title' => 'Your Logo Title'
);
```
* `src`: the image-url.
* `width`: the ratio of the logo in `em`
* `height`: the height of the logo in `px` or `em`
* `title`: the text in the invisable span for screenreader

## Usage

If you want to include the component in one of your template-files, just use

php
```php
  print component('factorial-io-components-logo', $your_array));
```
haml
```php
  = component('factorial-io-components-logo', $your_array)
```
 

