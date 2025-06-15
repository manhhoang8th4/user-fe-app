## flutter_ecommerce_app


![](https://github.com/SinaSys/flutter_ecommerce_app/blob/master/screenshots/screenshot.png?raw=true)


## Screenshots

Preview                    |   Home screen             |  Product Detail Screen    |  Cart Screen
:-------------------------:|:-------------------------:|:-------------------------:|:-------------------------:
![](https://github.com/SinaSys/flutter_ecommerce_app/blob/master/screenshots/preview.gif?raw=true)|![](https://github.com/SinaSys/flutter_ecommerce_app/blob/master/screenshots/home_screen.png?raw=true)|![](https://github.com/SinaSys/flutter_ecommerce_app/blob/master/screenshots/detail_screen.png?raw=true)|![](https://github.com/SinaSys/flutter_ecommerce_app/blob/master/screenshots/cart_screen.png?raw=true)

<br/>

## Directory Structure
```
📂lib
 │───main.dart  
 │───📂core  
 |   │──app_data.dart
 |   │──app_theme.dart
 |   │──app_color.dart
 |   └──extensions.dart
 └───📂src
     │────📂model
     │    │──product.dart
     |    │──product_category.dart
     |    │──product_size_type.dart
     |    │──recommended_product.dart
     |    │──categorical.dart
     |    │──numerical.dart
     |    └──bottom_navy_bar_item.dart
     └────📂view
     |    │───📂screen
     |    |   |──home_screen.dart
     |    |   |──product_list_screen.dart
     |    |   |──product_detail_screen.dart
     |    |   |──favorite_screen.dart
     |    |   |──cart_screen.dart
     |    |   └──profile_screen.dart
     |    │───📂widget
     |    |   |──carousel_slider.dart
     |    |   |──product_grid_view.dart
     |    |   |──list_item_selector.dart
     |    |   └──empty_cart.dart
     |    |   └──page_wrapper.dart
     |    └───📂animation
     |        |──animated_switcher_wrapper.dart
     |        └──open_container_wrapper.dart
     └────📂controller
          └──product_controller.dart
```




