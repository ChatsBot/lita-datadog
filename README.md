# lita-datadog

Interact with Datadog (https://www.datadoghq.com/).

## Installation

Add lita-datadog to your Lita instance's Gemfile:

``` ruby
gem "lita-datadog"
```

## Configuration

### Required attributes

You will need to get your API key, and configure an application key.  Go to https://app.datadoghq.com/account/settings#api for both.

* `api_key` (String) - Your DataDog API key. Default: `nil`
* `application_key` (String) - Your DataDog application key.  Default: `nil`

### Optional attributes

* `default_timerange` (Integer) - How long in seconds a default time range will be for graphs.  Default: `3600`

### Example

## Usage

```
Lita graph metric:"system.load.1{*},system.load.5{*}"
```

## License

[MIT](http://opensource.org/licenses/MIT)