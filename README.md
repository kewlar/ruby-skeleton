# Ruby skeleton

This is a skeleton repo for Ruby projects.

Code goes in `lib`. Tests go in `spec`.

## What's included

* [rspec](https://github.com/rspec/rspec) for testing.
* [rubocop](https://github.com/rubocop-hq/rubocop) with additional plugins and an opinionated configuration
  for code style checks.
* [byebug](https://github.com/deivid-rodriguez/byebug) and [pry](https://github.com/pry/pry) for debugging.
* [guard](https://github.com/guard/guard) and [growl](https://github.com/tj/growl) for auto-running tests and
  inspections.
* [rake](https://github.com/ruby/rake) for scripting tasks.

## Setting up

Install the dependencies:

```bash
bundle
```

Replace `lib/project.rb` and `spec/project_spec.rb` with your code.

## Development

Run guard, configured in red-green-refactor mode:

```bash
bundle exec guard
```
