# CHANGELOG
## master (unreleased)
### Added
- Form Tag Helpers

## 0.2.47 (2020-08-02)
### Fixed
- Highlighting for route paths

## 0.2.46 (2020-07-27)
### Fixed
- Highlighting for Active Record Relations

## 0.2.44 (2020-07-19)
### Fixed
- Highlighting for Named Routes

### Added
- Highlighting for Tag Helpers

## 0.2.43 (2020-07-08)
### Fixed
- Highlighting for Module, Active Storage methods.

## 0.2.42
### Fixed
- Highlighting for Routing - Resources, Scoping and HTTP Helpers.

## 0.2.41
### Fixed
- Highlighting for `has_rich_text`.

### Added
- Known `ActiveSupport::Rescuable::ClassMethods` Methods.

## 0.2.40
### Fixed
- Named Route Collection Methods when used as argument.

## 0.2.39
### Added
- Named Route Collection Methods (i.e. `foo_path`, `foo_url`).

## 0.2.38
### Added
- Known `ActionController::RequestForgeryProtection::ClassMethods` Methods.

## 0.2.37
### Fixed
- `select` method to differentiate Rails select vs Ruby Array#select

## 0.2.36
### Fixed
- Query Methods from highlighting when identified as variable.
- Differentiate Active Model Support Functions and Special Methods

## 0.2.35
### Added
- Known `ActionView::Helpers::CacheHelper` Methods

## 0.2.33
### Added
- Known `ActionController::Redirecting` Methods
- Known `ActionController::Flash::ClassMethods` Methods

### Changed
- Simplify Regex Lookbehinds

### Fixed
- Prevent Active Storage Attached Models from highlighting in Hash Keys

### Removed
- `gemfile` syntax as this is not Rails specific.
  - `gemfile` grammar added to [Ruby Syntax Highlighting](https://github.com/smridge/vscode-ruby-syntax)

## 0.2.32
### Added
- Known `ActionView::Helpers::TextHelper` methods.
- Known `ActionView::Helpers::TranslationHelper` methods.

## 0.2.31
### Added
- `ActionView::Helpers::UrlHelper`

## 0.2.3
### Fixed
- ActiveStorage Special Methods to require Symbol Argument.
- Associate `purge` and `purge_later` as Support Functions not Special Methods.
- Abstract Controller callbacks to require Symbol Argument.

## 0.2.2
### Fixed
- Disallowed preceeding characters for special methods.
- Gemfile Pattern Match for special methods.

## 0.2.1
### Fixed
- Space Requirement for Special Methods.

## 0.2.0
### Fixed
- Prevent Special Methods from highlighting when followed by characters with whitespace.

## 0.1.0
### Fixed
- Prevent Keywords from highlighting with preceeding dot.

### Change
- Differentiate Keywords and Functions.

## 0.0.9
### Fixed
- Prevent Highlighting in comments and strings for `gemfile`.

### Added
- `ActiveRecord::Enum` methods.

## 0.0.8
### Added
- `ActionDispatch::Routing::Mapper`

## 0.0.7
### Added
- `Bundler`: `gemfile`

### Fixed
- Prevent highlighting `gemfile` related scopes for other files.

## 0.0.6
### Added
- `Module < Object` methods.

## 0.0.5
### Added
- `ActiveRecord::Relation < Object` remaining methods.

## 0.0.4
### Added
- `ActiveRecord::Relation < Object` Part 1 methods.

### Fixed
- active_record scope query_methods pattern match to highlight when chaining methods.

## 0.0.3
### Added
- `ActiveModel::Validations::ClassMethods`

### Fixed
- Prevent Hash Keys from highlighting (invalid syntax).

## 0.0.1

### Added
- `AbstractController::Callbacks`
- `ActionText::Attribute`
- `ActiveRecord::Associations::ClassMethods`
- `ActiveRecord::Callbacks`
- `ActiveRecord::Migration < Object`
- `ActiveRecord::NestedAttributes::ClassMethods`
- `ActiveRecord::QueryMethods`
- `ActiveRecord::Scoping::Named::ClassMethods`
- `ActiveStorage::Attached::Model`
