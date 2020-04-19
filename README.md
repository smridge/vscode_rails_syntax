# Rails Syntax Highlighting for Visual Studio Code
Extends Visual Studio Code's Ruby Language Grammars with Rails Library.

Syntax Identification for Rails Library using [Rails API](https://api.rubyonrails.org).

## Known Methods Added from:

### AbstractController
- `AbstractController::Callbacks`

### ActionController
- `ActionController::Flash::ClassMethods`
- `ActionController::Redirecting`

### ActionDispatch
- `Routing::Mapper::Base`
- `Routing::Mapper::Concerns`
- `Routing::Mapper::CustomUrls`
- `Routing::Mapper::HttpHelpers`
- `Routing::Mapper::Resources`
- `Routing::Mapper::Scoping`

### ActionView
- `ActionView::Helpers::TextHelper`
- `ActionView::Helpers::TranslationHelper`
- `ActionView::Helpers::UrlHelper`

### ActionText
- `ActionText::Attribute`

### ActiveModel
- `ActiveModel::Validations::ClassMethods`

### ActiveRecord
- `ActiveRecord::Associations::ClassMethods`
- `ActiveRecord::Callbacks`
- `ActiveRecord::Enum`
- `ActiveRecord::Migration < Object`
- `ActiveRecord::NestedAttributes::ClassMethods`
- `ActiveRecord::QueryMethods`
- `ActiveRecord::Relation < Object`
- `ActiveRecord::Scoping::Named::ClassMethods`

### ActiveStorage
- `ActiveStorage::Attached::Model`

### Module
- `Module < Object`

## Notes
This Extension is certainly not inclusive of every method Rails offers. Rails is a massive library!

Pull Requests are more than welcome!

## References
[Syntax Highlight Guide](https://code.visualstudio.com/api/language-extensions/syntax-highlight-guide)

[Language Grammar Rules](https://macromates.com/manual/en/language_grammars)

[Rails API](https://api.rubyonrails.org)

## Related Extension

[Ruby Syntax Highlighting](https://github.com/smridge/vscode-ruby-syntax)
