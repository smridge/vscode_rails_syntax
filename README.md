# Rails Syntax Highlighting for Visual Studio Code
Extends Visual Studio Code's Ruby Language Grammars with Rails Library.

Syntax Identification for Rails Library using [Rails API](https://api.rubyonrails.org).

## Example Syntax Highlighting
### Before:
<img src="https://raw.githubusercontent.com/smridge/vscode_rails_syntax/master/images/before.png" width="400">

### After:
<img src="https://raw.githubusercontent.com/smridge/vscode_rails_syntax/master/images/after.png" width="400">


"Special Methods" such as `belongs_to`, `has_many`, `has_rich_text`, `validates`, `scope`, `before_action`, `link_to` are now identified.

There are certainly more known methods Rails provides. Added Methods from various classes/modules listed below.

## Known Methods Added

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
Install via [Visual Studio Code Extensions](https://marketplace.visualstudio.com/items?itemName=SarahRidge.vscode-rails-syntax)

[Syntax Highlight Guide](https://code.visualstudio.com/api/language-extensions/syntax-highlight-guide)

[Language Grammar Rules](https://macromates.com/manual/en/language_grammars)

[Rails API](https://api.rubyonrails.org)

## Related Extension

[Ruby Syntax Highlighting](https://github.com/smridge/vscode-ruby-syntax)

<br>

<img src="https://raw.githubusercontent.com/smridge/vscode_rails_syntax/master/images/icon.png" width="35"> Logo &copy;, David Heinemeier Hansson: https://rubyonrails.org/trademarks/
