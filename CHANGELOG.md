# Change Log

## [Released]
### [0.2.32]
#### Added
- `ActionView::Helpers::TextHelper`
- `ActionView::Helpers::TranslationHelper`

### [0.2.31]
#### Added
- `ActionView::Helpers::UrlHelper`

### [0.2.3]
#### Fixed
- ActiveStorage Special Methods to require Symbol Argument.
- Associate `purge` and `purge_later` as Support Functions not Special Methods.
- Abstract Controller callbacks to require Symbol Argument.

### [0.2.2]
#### Fixed
- Disallowed preceeding characters for special methods.
- Gemfile Pattern Match for special methods.

### [0.2.1]
#### Fixed
- Space Requirement for Special Methods.

### [0.2.0]
#### Fixed
- Prevent Special Methods from highlighting when followed by characters with whitespace.

### [0.1.0]
#### Fixed
- Prevent Keywords from highlighting with preceeding dot.

### Change
- Differentiate Keywords and Functions.

### [0.0.9]
#### Fixed
- Prevent Highlighting in comments and strings for `gemfile`.

#### Added
- `ActiveRecord::Enum` methods.

### [0.0.8]
#### Added
- `ActionDispatch::Routing::Mapper`

### [0.0.7]
#### Added
- `Bundler`: `gemfile`

#### Fixed
- Prevent highlighting `gemfile` related scopes for other files.

### [0.0.6]
#### Added
- `Module < Object` methods.

### [0.0.5]
#### Added
- `ActiveRecord::Relation < Object` remaining methods.

### [0.0.4]
#### Added
- `ActiveRecord::Relation < Object` Part 1 methods.

#### Fixed
- active_record scope query_methods pattern match to highlight when chaining methods.

### [0.0.3]
#### Added
- `ActiveModel::Validations::ClassMethods`

#### Fixed
- Prevent Hash Keys from highlighting (invalid syntax).

### [0.0.1]

#### Added
- `AbstractController::Callbacks`
- `ActionText::Attribute`
- `ActiveRecord::Associations::ClassMethods`
- `ActiveRecord::Callbacks`
- `ActiveRecord::Migration < Object`
- `ActiveRecord::NestedAttributes::ClassMethods`
- `ActiveRecord::QueryMethods`
- `ActiveRecord::Scoping::Named::ClassMethods`
- `ActiveStorage::Attached::Model`


## [Unreleased]
