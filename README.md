# Creamy Kit — Resources

Recursos compartilhados do **Creamy Kit** (design system): ícones e demais
assets consumidos pelos componentes.

> Repositório de **assets**. O código dos componentes vive no design system
> (`creamy-kit-angular` / `creamy-kit-react`).

## Estrutura

```
creamy-kit-resources/
└── icons/      373 ícones em SVG (Creamy Kit Icons, exportados do Figma)
```

## Iconset

São **373 ícones** em SVG. Maioria com pares `*_base` (filled) e `*_variant`
(outline). Para acompanharem a cor do tema, os componentes do design system
consomem os SVGs como `mask-image` pintados com `background-color:
currentColor` — veja `core/_icons.scss` em `creamy-kit-angular`.

### Uso direto (raw URL)

```
https://raw.githubusercontent.com/marinellibr/creamy-kit-resources/main/icons/<arquivo>.svg
```

Exemplo HTML:

```html
<img
  src="https://raw.githubusercontent.com/marinellibr/creamy-kit-resources/main/icons/arrow_right.svg"
  alt="" width="20" height="20" />
```

Exemplo SCSS (Creamy Kit Angular):

```scss
@use 'core/icons' as icons;

.my-icon { @include icons.icon('arrow_right', 20px); }
```

### Catálogo

| Nome | Arquivo |
| --- | --- |
| Background | `Background.svg` |
| Acne Base | `acne_base.svg` |
| Acne Skin Base | `acne_skin_base.svg` |
| Acne Skin Variant | `acne_skin_variant.svg` |
| Acne Variant | `acne_variant.svg` |
| Add Circle Base | `add_circle_base.svg` |
| Android Base | `android_base.svg` |
| Angular Variant | `angular_variant.svg` |
| Answer Base | `answer_base.svg` |
| Apple Base | `apple_base.svg` |
| Apply2 Base | `apply2_base.svg` |
| Apply2 Variant | `apply2_variant.svg` |
| Apply Base | `apply_base.svg` |
| Apply Variant | `apply_variant.svg` |
| Arrow Circle Down Base | `arrow_circle_down_base.svg` |
| Arrow Circle Down Variant | `arrow_circle_down_variant.svg` |
| Arrow Circle Left Base | `arrow_circle_left_base.svg` |
| Arrow Circle Left Variant | `arrow_circle_left_variant.svg` |
| Arrow Circle Right Base | `arrow_circle_right_base.svg` |
| Arrow Circle Right Variant | `arrow_circle_right_variant.svg` |
| Arrow Circle Up Base | `arrow_circle_up_base.svg` |
| Arrow Circle Up Variant | `arrow_circle_up_variant.svg` |
| Arrow Down | `arrow_down.svg` |
| Arrow Left | `arrow_left.svg` |
| Arrow Order Down | `arrow_order_down.svg` |
| Arrow Order Up | `arrow_order_up.svg` |
| Arrow Right | `arrow_right.svg` |
| Arrow Up | `arrow_up.svg` |
| At Sign Base | `at_sign_base.svg` |
| Attach Base | `attach_base.svg` |
| Back Space Base | `back_space_base.svg` |
| Back Space Variant | `back_space_variant.svg` |
| Barcode Base | `barcode_base.svg` |
| Bath Base | `bath_base.svg` |
| Bath Variant | `bath_variant.svg` |
| Battery Base | `battery_base.svg` |
| Battery Full Base | `battery_full_base.svg` |
| Battery Full Variant | `battery_full_variant.svg` |
| Battery Variant | `battery_variant.svg` |
| Blackhead Base | `blackhead_base.svg` |
| Blackhead Variant | `blackhead_variant.svg` |
| Blob Base | `blob_base.svg` |
| Blob Variant | `blob_variant.svg` |
| Bookmark Base | `bookmark_base.svg` |
| Bookmark Variant | `bookmark_variant.svg` |
| Bottle Base | `bottle_base.svg` |
| Bottle Variant | `bottle_variant.svg` |
| Box Base | `box_base.svg` |
| Box Variant | `box_variant.svg` |
| Bubble Base | `bubble_base.svg` |
| Bubble Variant | `bubble_variant.svg` |
| Calendar Clock Base | `calendar_clock_base.svg` |
| Calendar Day Base | `calendar_day_base.svg` |
| Calendar Day Variant | `calendar_day_variant.svg` |
| Calendar Month Base | `calendar_month_base.svg` |
| Calendar Month Variant | `calendar_month_variant.svg` |
| Calming Cream Base | `calming_cream_base.svg` |
| Calming Cream Variant | `calming_cream_variant.svg` |
| Camera Base | `camera_base.svg` |
| Camera Variant | `camera_variant.svg` |
| Camera Video Base | `camera_video_base.svg` |
| Camera Video Variant | `camera_video_variant.svg` |
| Card Payment Method Base | `card_payment_method_base.svg` |
| Card Payment Method Variant | `card_payment_method_variant.svg` |
| Chat Information Base | `chat_information_base.svg` |
| Chat Information Variant | `chat_information_variant.svg` |
| Chat Lines Base | `chat_lines_base.svg` |
| Chat Lines Variant | `chat_lines_variant.svg` |
| Chat Message Base | `chat_message_base.svg` |
| Chat Message Variant | `chat_message_variant.svg` |
| Check Base | `check_base.svg` |
| Check Circle Base | `check_circle_base.svg` |
| Check Circle Variant | `check_circle_variant.svg` |
| Check Double Small Base | `check_double_small_base.svg` |
| Check Small Base | `check_small_base.svg` |
| Checkbox Base | `checkbox_base.svg` |
| Checkbox Unchecked Base | `checkbox_unchecked_base.svg` |
| Checkbox Unchecked Variant | `checkbox_unchecked_variant.svg` |
| Checkbox Undetermined Base | `checkbox_undetermined_base.svg` |
| Checkbox Undetermined Variant | `checkbox_undetermined_variant.svg` |
| Checkbox Variant | `checkbox_variant.svg` |
| Circle Base | `circle_base.svg` |
| Circle Variant | `circle_variant.svg` |
| Cleaning Gel Base | `cleaning_gel_base.svg` |
| Cleaning Gel Variant | `cleaning_gel_variant.svg` |
| Clock Base | `clock_base.svg` |
| Clock Small Base | `clock_small_base.svg` |
| Clock Small Variant | `clock_small_variant.svg` |
| Clock Variant | `clock_variant.svg` |
| Close Base | `close_base.svg` |
| Cloud Base | `cloud_base.svg` |
| Cloud Variant | `cloud_variant.svg` |
| Code Base | `code_base.svg` |
| Cold Base | `cold_base.svg` |
| Combination Skin Base | `combination_skin_base.svg` |
| Combination Skin Variant | `combination_skin_variant.svg` |
| Configuration Base | `configuration_base.svg` |
| Configuration Variant | `configuration_variant.svg` |
| Contact Book Base-1 | `contact_book_base-1.svg` |
| Contact Book Base | `contact_book_base.svg` |
| Copy Base | `copy_base.svg` |
| Copy Variant | `copy_variant.svg` |
| Cruelty Free Variant-1 | `cruelty_free_variant-1.svg` |
| Cruelty Free Variant | `cruelty_free_variant.svg` |
| Day And Night Base | `day_and_night_base.svg` |
| Day And Night Variant | `day_and_night_variant.svg` |
| Day Base | `day_base.svg` |
| Day Variant | `day_variant.svg` |
| Debit Payment Method Base | `debit_payment_method_base.svg` |
| Debit Payment Method Variant | `debit_payment_method_variant.svg` |
| Dermatologically Tested Base | `dermatologically_tested_base.svg` |
| Dermatologically Tested Variant | `dermatologically_tested_variant.svg` |
| Desktop Base | `desktop_base.svg` |
| Desktop Variant | `desktop_variant.svg` |
| Discount Base | `discount_base.svg` |
| Discount Variant | `discount_variant.svg` |
| Dislike Base | `dislike_base.svg` |
| Dislike Variant | `dislike_variant.svg` |
| Dollar Sign Base | `dollar_sign_base.svg` |
| Dots Horizontal Base | `dots_horizontal_base.svg` |
| Download Base | `download_base.svg` |
| Drag And Drop Base | `drag_and_drop_base.svg` |
| Dry Skin Base | `dry_skin_base.svg` |
| Dry Skin Variant | `dry_skin_variant.svg` |
| Duo Base | `duo_base.svg` |
| Duo Variant | `duo_variant.svg` |
| Edit-base | `edit-base.svg` |
| Edit-variant | `edit-variant.svg` |
| Email Base | `email_base.svg` |
| Email Variant | `email_variant.svg` |
| Error Circle Base | `error_circle_base.svg` |
| Error Circle Variant | `error_circle_variant.svg` |
| Euro Sign Base | `euro_sign_base.svg` |
| Exfoliation Base | `exfoliation_base.svg` |
| Exfoliation Variant | `exfoliation_variant.svg` |
| Exit Base | `exit_base.svg` |
| External Link Base | `external_link_base.svg` |
| Eye Off Base | `eye_off_base.svg` |
| Eye Off Variant | `eye_off_variant.svg` |
| Face Mask Base | `face_mask_base.svg` |
| Face Mask Variant | `face_mask_variant.svg` |
| Facebook Base | `facebook_base.svg` |
| Facebook Variant | `facebook_variant.svg` |
| Festival Base | `festival_base.svg` |
| Festival Variant | `festival_variant.svg` |
| Filter Base | `filter_base.svg` |
| Filter Variant | `filter_variant.svg` |
| Flag Base | `flag_base.svg` |
| Flag Variant | `flag_variant.svg` |
| Flash Off Base | `flash_off_base.svg` |
| Flash Off Variant | `flash_off_variant.svg` |
| Flash On Base | `flash_on_base.svg` |
| Flash On Variant | `flash_on_variant.svg` |
| Flow Base | `flow_base.svg` |
| Flow Variant | `flow_variant.svg` |
| Foam Hand Base | `foam_hand_base.svg` |
| Foam Hand Variant | `foam_hand_variant.svg` |
| Fragrance Base | `fragrance_base.svg` |
| Fragrance Variant | `fragrance_variant.svg` |
| Gift Base | `gift_base.svg` |
| Gift Variant | `gift_variant.svg` |
| Glow Base | `glow_base.svg` |
| Glow Variant | `glow_variant.svg` |
| Hairdryer Base | `hairdryer_base.svg` |
| Hairdryer Variant | `hairdryer_variant.svg` |
| Health Base | `health_base.svg` |
| Health Variant | `health_variant.svg` |
| Heart Base | `heart_base.svg` |
| Heart Health Base | `heart_health_base.svg` |
| Heart Health Variant | `heart_health_variant.svg` |
| Heart Variant | `heart_variant.svg` |
| Help Base | `help_base.svg` |
| Help Variant | `help_variant.svg` |
| House Base | `house_base.svg` |
| House Variant | `house_variant.svg` |
| Html5 Variant | `html5_variant.svg` |
| Hydration Base | `hydration_base.svg` |
| Hydration Variant | `hydration_variant.svg` |
| Information Base | `information_base.svg` |
| Information Variant | `information_variant.svg` |
| Instagram Base-1 | `instagram_base-1.svg` |
| Instagram Base | `instagram_base.svg` |
| Key Base | `key_base.svg` |
| Key Variant | `key_variant.svg` |
| Layout Base | `layout_base.svg` |
| Light Base | `light_base.svg` |
| Like Base | `like_base.svg` |
| Like Variant | `like_variant.svg` |
| Linkedin Base | `linkedin_base.svg` |
| Linkedin Variant | `linkedin_variant.svg` |
| Lip Balm Base | `lip_balm_base.svg` |
| Lip Balm Variant | `lip_balm_variant.svg` |
| Lips Base | `lips_base.svg` |
| List Base | `list_base.svg` |
| Loading Base | `loading_base.svg` |
| Lock Base | `lock_base.svg` |
| Lock Variant | `lock_variant.svg` |
| Math Base | `math_base.svg` |
| Mature Skin Base | `mature_skin_base.svg` |
| Mature Skin Variant | `mature_skin_variant.svg` |
| Medal Base | `medal_base.svg` |
| Medal Variant | `medal_variant.svg` |
| Menu Base | `menu_base.svg` |
| Mic Off Base | `mic_off_base.svg` |
| Microphone  variant | `microphone_ variant.svg` |
| Microphone Base | `microphone_base.svg` |
| Mobile  base | `mobile_ base.svg` |
| Mobile Variant | `mobile_variant.svg` |
| Night Base | `night_base.svg` |
| Night Variant | `night_variant.svg` |
| No Fragrance Base | `no_fragrance_base.svg` |
| No Fragrance Variant | `no_fragrance_variant.svg` |
| Normal Skin Base | `normal_skin_base.svg` |
| Normal Skin Variant | `normal_skin_variant.svg` |
| Notification Base | `notification_base.svg` |
| Notification Variant | `notification_variant.svg` |
| Oily Skin Base | `oily_skin_base.svg` |
| Oily Skin Variant | `oily_skin_variant.svg` |
| Orders Base | `orders_base.svg` |
| Orders Variant | `orders_variant.svg` |
| Percent Base | `percent_base.svg` |
| Phone Base | `phone_base.svg` |
| Phone Variant | `phone_variant.svg` |
| Pin Base | `pin_base.svg` |
| Pin Variant | `pin_variant.svg` |
| Pix Base | `pix_base.svg` |
| Pix Variant | `pix_variant.svg` |
| Place Base | `place_base.svg` |
| Place Variant | `place_variant.svg` |
| Play Big Variant | `play_big_variant.svg` |
| Plus Base | `plus_base.svg` |
| Pores Base | `pores_base.svg` |
| Pores Variant | `pores_variant.svg` |
| Qr Code Base | `qr_code_base.svg` |
| Qr Code Variant | `qr_code_variant.svg` |
| Radio Button Base | `radio_button_base.svg` |
| Radio Button Variant | `radio_button_variant.svg` |
| React Base | `react_base.svg` |
| Recyclable Base | `recyclable_base.svg` |
| Refil Base | `refil_base.svg` |
| Reload Base | `reload_base.svg` |
| Running Water Base | `running_water_base.svg` |
| Running Water Variant | `running_water_variant.svg` |
| Sad Face Base | `sad_face_base.svg` |
| Sad Face Variant | `sad_face_variant.svg` |
| Save Base | `save_base.svg` |
| Save Variant | `save_variant.svg` |
| Science Base | `science_base.svg` |
| Science Variant | `science_variant.svg` |
| Search Base | `search_base.svg` |
| Search Variant | `search_variant.svg` |
| Security Base | `security_base.svg` |
| Security Check Base | `security_check_base.svg` |
| Security Check Variant | `security_check_variant.svg` |
| Security Error Base | `security_error_base.svg` |
| Security Error Variant | `security_error_variant.svg` |
| Security Variant | `security_variant.svg` |
| Send Base | `send_base.svg` |
| Send Variant | `send_variant.svg` |
| Sensitive Skin Base | `sensitive_skin_base.svg` |
| Sensitive Skin Variant | `sensitive_skin_variant.svg` |
| Share Base | `share_base.svg` |
| Shopping Bag Base | `shopping_bag_base.svg` |
| Shopping Bag Variant | `shopping_bag_variant.svg` |
| Shopping Cart Base | `shopping_cart_base.svg` |
| Shopping Cart Variant | `shopping_cart_variant.svg` |
| Shopping Mall Base-1 | `shopping_mall_base-1.svg` |
| Shopping Mall Base | `shopping_mall_base.svg` |
| Shower Base | `shower_base.svg` |
| Shower Variant | `shower_variant.svg` |
| Skin Glow Base | `skin_glow_base.svg` |
| Skin Glow Variant | `skin_glow_variant.svg` |
| Skincare Kit Base | `skincare_kit_base.svg` |
| Skincare Kit Variant | `skincare_kit_variant.svg` |
| Smartwatch Base-1 | `smartwatch_base-1.svg` |
| Smartwatch Base | `smartwatch_base.svg` |
| Smile Base | `smile_base.svg` |
| Smile Variant | `smile_variant.svg` |
| Smile Wink Base | `smile_wink_base.svg` |
| Smile Wink Variant | `smile_wink_variant.svg` |
| Sound Off Base | `sound_off_base.svg` |
| Sound On Base | `sound_on_base.svg` |
| Spa Base | `spa_base.svg` |
| Spotify Base | `spotify_base.svg` |
| Spotify Variant | `spotify_variant.svg` |
| Spray Base | `spray_base.svg` |
| Spray Variant | `spray_variant.svg` |
| Squares Base | `squares_base.svg` |
| Squares Variant | `squares_variant.svg` |
| Star Base | `star_base.svg` |
| Star Variant | `star_variant.svg` |
| Stethoscope Base | `stethoscope_base.svg` |
| Stethoscope Variant | `stethoscope_variant.svg` |
| Stop Big Variant | `stop_big_variant.svg` |
| Store Base | `store_base.svg` |
| Store Variant | `store_variant.svg` |
| Sun Off Base | `sun_off_base.svg` |
| Sun Off Variant | `sun_off_variant.svg` |
| Sun Protection Base | `sun_protection_base.svg` |
| Sun Protection Variant | `sun_protection_variant.svg` |
| Sunscreen Base | `sunscreen_base.svg` |
| Sunscreen Variant | `sunscreen_variant.svg` |
| Sustainabillity Base | `sustainabillity_base.svg` |
| Sustainabillity Variant | `sustainabillity_variant.svg` |
| Swift Variant | `swift_variant.svg` |
| Switch Base | `switch_base.svg` |
| Switch Variant | `switch_variant.svg` |
| Tablet Base | `tablet_base.svg` |
| Tablet Variant | `tablet_variant.svg` |
| Tag Base | `tag_base.svg` |
| Tag Variant | `tag_variant.svg` |
| Target Base | `target_base.svg` |
| Target Variant | `target_variant.svg` |
| Television Base | `television_base.svg` |
| Television Variant | `television_variant.svg` |
| Temperature Base | `temperature_base.svg` |
| Temperature Variant | `temperature_variant.svg` |
| Templates Base | `templates_base.svg` |
| Test Tube Base | `test_tube_base.svg` |
| Test Tube Variant | `test_tube_variant.svg` |
| Textbox Base | `textbox_base.svg` |
| Tik Tok Base | `tik_tok_base.svg` |
| Tik Tok Variant | `tik_tok_variant.svg` |
| Tonic Base | `tonic_base.svg` |
| Tonic Variant | `tonic_variant.svg` |
| Transport Truck Base | `transport_truck_base.svg` |
| Transport Truck Variant | `transport_truck_variant.svg` |
| Trash Base | `trash_base.svg` |
| Trash Variant | `trash_variant.svg` |
| Umbrella Base-1 | `umbrella_base-1.svg` |
| Umbrella Base | `umbrella_base.svg` |
| Unlocked Base-1 | `unlocked_base-1.svg` |
| Unlocked Base | `unlocked_base.svg` |
| Upload Base | `upload_base.svg` |
| User Base | `user_base.svg` |
| User Group Base-1 | `user_group_base-1.svg` |
| User Group Base | `user_group_base.svg` |
| User Variant | `user_variant.svg` |
| Vegan Base | `vegan_base.svg` |
| Vegan Variant | `vegan_variant.svg` |
| Video Pause Base | `video_pause_base.svg` |
| Video Pause Variant | `video_pause_variant.svg` |
| Video Play Base | `video_play_base.svg` |
| Video Play Variant | `video_play_variant.svg` |
| Video Stop Base | `video_stop_base.svg` |
| Video Stop Variant | `video_stop_variant.svg` |
| Visibility Off | `visibility_off_.svg` |
| Visibility On Base | `visibility_on_base.svg` |
| Visibility On Variant | `visibility_on_variant.svg` |
| Vitamin C Base-1 | `vitamin_c_base-1.svg` |
| Vitamin C Base | `vitamin_c_base.svg` |
| Vitamin C Variant-1 | `vitamin_c_variant-1.svg` |
| Vitamin C Variant | `vitamin_c_variant.svg` |
| Wallet Base | `wallet_base.svg` |
| Wallet Variant | `wallet_variant.svg` |
| Warning Base | `warning_base.svg` |
| Warning Small Base | `warning_small_base.svg` |
| Warning Small Variant | `warning_small_variant.svg` |
| Warning Variant | `warning_variant.svg` |
| Water Base | `water_base.svg` |
| Water Variant | `water_variant.svg` |
| Whatsapp Base | `whatsapp_base.svg` |
| Whatsapp Variant | `whatsapp_variant.svg` |
| Wifi Base | `wifi_base.svg` |
| Wind Base | `wind_base.svg` |
| Wind Variant | `wind_variant.svg` |
| Window Maximize Base | `window_maximize_base.svg` |
| Window Minimize Base | `window_minimize_base.svg` |
| Window Retore Base | `window_retore_base.svg` |
| X Base | `x_base.svg` |
| X Variant | `x_variant.svg` |
| Youtube Base | `youtube_base.svg` |
| Youtube Variant | `youtube_variant.svg` |

## Contribuindo

1. Adicione o SVG em `icons/` usando o mesmo padrão de nome
   (`<nome>_base.svg` para filled, `<nome>_variant.svg` para outline).
2. Mantenha o `viewBox` quadrado.
3. Atualize a tabela acima (entrada por arquivo).
