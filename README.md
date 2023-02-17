# Rails Syntax Highlighting for Visual Studio Code
[![Published Version to VS Code](https://img.shields.io/visual-studio-marketplace/v/SarahRidge.vscode-rails-syntax)](https://marketplace.visualstudio.com/items?itemName=SarahRidge.vscode-rails-syntax)
[![VS Code Downloads](https://img.shields.io/visual-studio-marketplace/d/SarahRidge.vscode-rails-syntax)](https://marketplace.visualstudio.com/items?itemName=SarahRidge.vscode-rails-syntax)
[![VS Code Installs](https://img.shields.io/visual-studio-marketplace/i/SarahRidge.vscode-rails-syntax)](https://marketplace.visualstudio.com/items?itemName=SarahRidge.vscode-rails-syntax)
[![GitHub License](https://img.shields.io/github/license/smridge/vscode_rails_syntax.svg)](https://github.com/smridge/vscode_rails_syntax/blob/master/LICENSE)

Extends Visual Studio Code's Ruby Language Grammars with the Rails Library.

Support methods are identified such as:
- `belongs_to`
- `has_many`
- `has_rich_text`
- `validates`
- `scope`
- `before_action`
- `link_to`

This extension is certainly not inclusive of every method Rails and Turbo Rails offers. Rails is a massive library! Added methods from various classes/modules listed below.

Pull Requests are more than welcome!

## Install
- Run: `code --install-extension SarahRidge.vscode-rails-syntax`
  - Alternatively, extension can be installed via [VScode marketplace](https://marketplace.visualstudio.com/items?itemName=SarahRidge.vscode-rails-syntax).
- Reload VSCode.

## Known Methods Added From

### AbstractController
- `AbstractController::Callbacks`

### ActionController
- `ActionController::Flash::ClassMethods`
- `ActionController::Redirecting`
- `ActionController::RequestForgeryProtection::ClassMethods`

### ActionDispatch
- `Routing::Mapper::Base`
- `Routing::Mapper::Concerns`
- `Routing::Mapper::CustomUrls`
- `Routing::Mapper::HttpHelpers`
- `Routing::Mapper::Resources`
- `Routing::Mapper::Scoping`

### ActionView
- `ActionView::Helpers::CacheHelper`
- `ActionView::Helpers::FormTagHelper`
- `ActionView::Helpers::TagHelper`
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

### ActiveSupport
- `ActiveSupport::Rescuable::ClassMethods`

### Module
- `Module < Object`

### Turbo Rails
- `Turbo::FramesHelper`
- `Turbo::Streams::ActionHelper`
- `Turbo::Streams::TagBuilder`
- `Turbo::StreamsHelper`

## References
- [Syntax Highlight Guide](https://code.visualstudio.com/api/language-extensions/syntax-highlight-guide)
- [Language Grammar Rules](https://macromates.com/manual/en/language_grammars)
- [Rails API](https://api.rubyonrails.org)
- [Turbo Rails API](https://github.com/hotwired/turbo-rails)

## Related Extensions
- [Ruby Syntax Highlighting](https://github.com/smridge/vscode-ruby-syntax)

## Contributors
<a href="https://github.com/smridge/vscode_rails_syntax/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=smridge/vscode_rails_syntax" />
</a>

<br>

<img src="https://raw.githubusercontent.com/smridge/vscode_rails_syntax/master/images/icon.png" width="35"> Logo &copy; David Heinemeier Hansson: https://rubyonrails.org/trademarks/
