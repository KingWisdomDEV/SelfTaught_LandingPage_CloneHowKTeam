sass/
|
|– abstracts/ (or utilities/)
|   |– _variables.scss    // Sass Variables
|   |– _functions.scss    // Sass Functions
|   |– _mixins.scss       // Sass Mixins
|
|– base/
|   |– _reset.scss        // Reset/normalize
|   |– _typography.scss   // Typography rules
|
|– components/ (or modules/)
|   |– _buttons.scss      // Buttons
|   |– _carousel.scss     // Carousel
|   |– _slider.scss       // Slider
|
|– layout/
|   |– _navigation.scss   // Navigation
|   |– _grid.scss         // Grid system
|   |– _header.scss       // Header
|   |– _footer.scss       // Footer
|   |– _sidebar.scss      // Sidebar
|   |– _forms.scss        // Forms
|
|– pages/
|   |– _home.scss         // Home specific styles
|   |– _about.scss        // About specific styles
|   |– _contact.scss      // Contact specific styles
|
|– themes/
|   |– _theme.scss        // Default theme
|   |– _admin.scss        // Admin theme
|
|– vendors/
|   |– _bootstrap.scss    // Bootstrap
|   |– _jquery-ui.scss    // jQuery UI
|
`– main.scss              // Main Sass file


- Abstracts (hay ultilities) : chứa các CSS helper bao gồm biến, functions, mixins....

- Base : chứa các boilerplate code (có thể hiểu chung là code được áp dụng chung cho toàn bộ project của bạn như typographic rules hay reset rules....

- Components (hay modules) : Thư mục này chứa code cho các thành phần (components) mà có thể reusable cho trang của bạn như buttons, forms, cards, v.v..

- Layout : Chứa code định nghĩa cho layout của project như header, footer, navigation, grid,....

- Pages: Một dự án lớn sẽ chứa rất nhiều page khác nhau với nhiều style khác nhau. Đây là nơi bạn định nghĩa style cho từng trang.

- Themes: Nếu trang của bạn có nhiều hơn 1 theme, bạn sẽ định nghĩa tại đây.

- Vendors: chứa các files từ bên thứ ba ( thư viện, framworks) bạn sử dụng như Normalize, Bootstrap, jQuery,....Tuy nhiên trong thực tế bạn sẽ thường xuyên override code ( hiểu đơn giản là sửa một vài phần code theo ý mình). Nên nếu cần thiết, bạn có thể tạo thêm 1 folder khác vendors-extensions/ để chứa các override files của mình.