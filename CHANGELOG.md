# Change Log

All notable changes to the "new-dark" extension will be documented in this file.

## 1.2.3 (2023-09-19)

### Fixed

- adjust highlighting color for template literal braces ([486ee04](https://github.com/eenaree/new-dark-theme/commit/486ee04d660a6adb70c75f74409b7de397e7a86f))
- adjust colors for notification ([e0cb2d9](https://github.com/eenaree/new-dark-theme/commit/e0cb2d96d715febab4b060ba2205c3bc0152de20))
- remove semantic token colors for functions and methods to enable differentiation based on their types ([c8cf12a](https://github.com/eenaree/new-dark-theme/commit/c8cf12a340d329cbfbda87e5d3b6e8863d9a41ac))
- [#2](https://github.com/eenaree/new-dark-theme/issues/2) secondary button that appears transparent

## 1.2.2 (2023-09-17)

### Fixed

- in Hover Widget, highlight color of token to be more accurate

  - type parameter [#1](https://github.com/eenaree/new-dark-theme/issues/1)
  - variable ([6211559](https://github.com/eenaree/new-dark-theme/commit/6211559ba0746d8da57e94f68042404443463da9))

- adjust highlight color for jsx component token ([07d046a](https://github.com/eenaree/new-dark-theme/commit/07d046aca4644f6b50897d421b6e269ea8ebc397))

## 1.2.1 (2023-09-16)

### Fixed

- highlight color for decorator more accurate ([c6b85bf](https://github.com/eenaree/new-dark-theme/commit/c6b85bf9bd4b416996124764e55a7b4e715d98b3))
- highlight color for percentage keyword, rgb color code, tagged template function ([a495bae](https://github.com/eenaree/new-dark-theme/commit/a495bae12f2adb06c2feafecea897b53cf828609))
- unnecessary highlighting for type declaration brace ([84b6577](https://github.com/eenaree/new-dark-theme/commit/84b6577390362f3f146d73c1fe5815a465772344))

## 1.2.0 (2023-09-16)

### Added

- divide theme into `Webstorm New Dark` and `Webstorm New Darcula` version ([e9c6811](https://github.com/eenaree/new-dark-theme/commit/e9c68114c044f3565ddf92970512480bca8a2802))

### Fixed

- adjust overall token color more accurate ([713ae7f](https://github.com/eenaree/new-dark-theme/commit/713ae7f876d48a4f1f71b322b9f10cd5d5d8db70))
- in `Webstorm New Darcula`
  - fix selected menu item more visible ([3782b82](https://github.com/eenaree/new-dark-theme/commit/3782b82e2659bde3bc4f034e774837aa76ee73c5))
  - make color for dropdown more accurate ([e530b7d](https://github.com/eenaree/new-dark-theme/commit/e530b7d136ad87e7738c7c73a53fa4b7289d2c90))
  - rollback of hover and drop background for list ([ec58533](https://github.com/eenaree/new-dark-theme/commit/ec58533e18fb544104a3bcab61e46928d261af62))

## 1.1.7 (2023-09-13)

### Fixed

- color for jsx component token ([20da8b7](https://github.com/eenaree/new-dark-theme/commit/20da8b75885553c6f98ac5e2e34086b3f62fa27f)), type parameter ([524590f](https://github.com/eenaree/new-dark-theme/commit/524590f38709275e89963c7aec083af8f04da4eb))
- border for active tab and panel ([8661d48](https://github.com/eenaree/new-dark-theme/commit/8661d48059362b23dd0ec652670358699a892b4f))
- background for other badge except activity bar ([60abc02](https://github.com/eenaree/new-dark-theme/commit/60abc02b57309eb62604e92ca2352a71a898b34b))
- background for button and secondary button ([fc13f1a](https://github.com/eenaree/new-dark-theme/commit/fc13f1a8601bf9450cf6331f746d23367e73f4cd))
- background when empty editor group ([b93130c](https://github.com/eenaree/new-dark-theme/commit/b93130c77a452e9e3e37a5419ef0f46f65dd52c5))
- background for folded range ([2f9befd](https://github.com/eenaree/new-dark-theme/commit/2f9befd5435d939a5d270ae891e8ac32c4a7ee6e))
- simplify matching brackets color ([61aec28](https://github.com/eenaree/new-dark-theme/commit/61aec289d76f03ddaa763e483c33520fffa4a071))
- adjust colors when list hover and focused to match WebStorm ([eb6bfed](https://github.com/eenaree/new-dark-theme/commit/eb6bfed7f9b334d60506613e81fec513398a7f7c))
- diff editor to make changes more visible ([fa13660](https://github.com/eenaree/new-dark-theme/commit/fa1366070bcc8b012e4bd04e51365561339b2bc4))
- colors for settings editor ([641aab2](https://github.com/eenaree/new-dark-theme/commit/641aab26fbc4137fb70939da9d49f1254f088ea9))
- colors for editor suggest widget ([106674a](https://github.com/eenaree/new-dark-theme/commit/106674a36866955db5af92a2be2365f067c53155)), hover widget ([9c16351](https://github.com/eenaree/new-dark-theme/commit/9c1635124b56f591f2830f5c875b7154796a5f49))
- color for triple backtick in markdown code block ([68c0c8e](https://github.com/eenaree/new-dark-theme/commit/68c0c8eded5a0ef201434301b74c77ecafeac215))
- divide background for inline hints into type and parameter ([d12e5bf](https://github.com/eenaree/new-dark-theme/commit/d12e5bf620065282968331da0ca60fac90a572a1))
- default color for uncolored tokens ([9366cf0](https://github.com/eenaree/new-dark-theme/commit/9366cf08cc68a46885877a3199678706bf6e0e5c))

## 1.1.6 (2023-08-29)

### Improved

- highlighting for vendored css properties, keyframes and variables ([5fedddb](https://github.com/eenaree/new-dark-theme/commit/5fedddb1bb4eda076947c0e51423140b5099c2ee))

### Fixed

- color for terminator statement, like semicolon ([2473297](https://github.com/eenaree/new-dark-theme/commit/2473297cbd4c72467c5c87b2fad096c375918125))
- color for jsx attribute assignment keyword ([e9b8f76](https://github.com/eenaree/new-dark-theme/commit/e9b8f763e60d1e2ed6d13d459f9e33369dab2e44))
- restrict supported constant and function colors in source.css ([0c8df2d](https://github.com/eenaree/new-dark-theme/commit/0c8df2dc83155e6ebb76e19beafe492a8d3b9cb9))
- color for terminal, inactive panel title to match WebStorm ([2d657f3](https://github.com/eenaree/new-dark-theme/commit/2d657f3a60120709de3423e15569b4f99c1ac905))
- colors for class, constant property, arrow function and module.exports statement to match WebStorm ([b9e9cf8](https://github.com/eenaree/new-dark-theme/commit/b9e9cf89c251746da0ad0e817965f11a26dc57d5))

## 1.1.5 (2023-08-26)

### Improved

- editor's peek view color to match WebStorm ([bd6c45a](https://github.com/eenaree/new-dark-theme/commit/bd6c45a374b90669f913873edf413a9099f948ca))

### Fixed

- simplify constant.language scope for cross-language consistency ([1b3ef39](https://github.com/eenaree/new-dark-theme/commit/1b3ef39c676ba96bba81f2ba1c870d41ba530a4f))
- background color of the selected item ([eb3a255](https://github.com/eenaree/new-dark-theme/commit/eb3a255ede62a46afbd15b87c7493e3d78769150))

## 1.1.4 (2023-08-25)

### Improved

- syntax highlight for type, interface, function, method, and property using semantic token colors ([eff7c2e](https://github.com/eenaree/new-dark-theme/commit/eff7c2ee643ecf6a1d3cd2867f4a087bf1804322))
- regular expression syntax highlight ([dc21fca](https://github.com/eenaree/new-dark-theme/commit/dc21fca955cd7124d01ac276e9ec835bc7a165bd))

### Fixed

- font style for variable and class's default library ([850a777](https://github.com/eenaree/new-dark-theme/commit/850a77746a89fd3945789aa69afb9ac77b317778))
- css color value highlight ([4c495fe](https://github.com/eenaree/new-dark-theme/commit/4c495fe781480dd48dd92e606057441715ecc722))

## 1.1.3 (2023-08-20)

### Improved

- find, selection, word highlight to match WebStorm ([fce6605](https://github.com/eenaree/new-dark-theme/commit/fce66054fac5903f4f03d1464ac3c39af99a8fd3))
- diff editor background color ([e804a0b](https://github.com/eenaree/new-dark-theme/commit/e804a0b6f2c42c9bf136346b0d8506d61a234fe2))
- color for git resources to match WebStorm ([b7085b3](https://github.com/eenaree/new-dark-theme/commit/b7085b38353c5b8761f23fd57d484e1bee2cd023))
- html, css syntax highlight to match WebStorm ([c69f31b](https://github.com/eenaree/new-dark-theme/commit/c69f31b1ed2bed88d898c357ea4d3dd79f994692))
- markdown syntax highlight to match WebStorm ([befa0b8](https://github.com/eenaree/new-dark-theme/commit/befa0b8d113ed1d87085184ef480aa2fc23b4d09))

## 1.1.2 (2023-08-18)

### Fixed

- colors for bracket and search match string ([8b071a6](https://github.com/eenaree/new-dark-theme/commit/8b071a6883be32b2e2e79fddf502b840c58d26cb))
- color scheme for diff editor, merge conflict, and editor gutter line to match WebStorm's new UI Color ([7a14470](https://github.com/eenaree/new-dark-theme/commit/7a144709a60533fd49e5661e2409ef292a9167d4))
- update selectors from `#b3ae60` color scope to `#d5b778` color scope for consistency ([779d9a8](https://github.com/eenaree/new-dark-theme/commit/779d9a8ab1d2ddbf0f15df3e8e63b24fd0854a6b))

## 1.1.1 (2023-08-16)

### Fixed

- markdown heading's highlighting color ([16708a6](https://github.com/eenaree/new-dark-theme/commit/16708a64193ff2904309560d46c07e53d78e7676))

## 1.1.0 (2023-08-10)

### Added

- support for jsx component highlighting ([3b09e81](https://github.com/eenaree/new-dark-theme/commit/3b09e8139dee3c9895ac8785761a824ed184da9d))
- support for markdown syntax highlighting ([ce3423e](https://github.com/eenaree/new-dark-theme/commit/ce3423e9c60d171cbd2d13b240670ea3e0438b9c))

### Fixed

- remove semantic color for class declaration ([1f6403d](https://github.com/eenaree/new-dark-theme/commit/1f6403dcff1e53823a5b28190f049ca90bdb8774))

## 1.0.2 (2023-08-09)

### Fixed

- color for support property ([c4404cf](https://github.com/eenaree/new-dark-theme/commit/c4404cf7ccde6303b782b8eab50568329116f46a))

## 1.0.1 (2023-08-08)

### Fixed

- object property accessor color in template literals ([60bf715](https://github.com/eenaree/new-dark-theme/commit/60bf71561d695b26fffcc25261461ba28cbd650a))
- default color for keyword.operator ([ba35373](https://github.com/eenaree/new-dark-theme/commit/ba35375f5b17e09f79570c3f2dba2578c3a03e21))

## 1.0.0 (2023-08-07)

- Initial release
