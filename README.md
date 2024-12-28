Here is the app structure of our this EMS App:
lib
├── models
│   ├── event_model.dart
│   └── user_model.dart
│
├── services
│   ├── auth_service.dart
│   ├── chat_service.dart
│   ├── event_service.dart
│   └── firebase_storage_service.dart
│
├── utils
│   ├── animations.dart
│   ├── constants.dart
│   ├── helpers.dart
│   ├── theme.dart
│   └── theme_provider.dart
│
├── views
│   ├── admin
│   │   ├── admin_dashboard_screen.dart
│   │   ├── event_registration_screen.dart
│   │   ├── event_schedule_screen.dart
│   │   └── ticketing_screen.dart
│   │
│   ├── auth
│   │   ├── login_screen.dart
│   │   └── signup_screen.dart
│   │
│   ├── common
│   │   ├── chat_screen.dart
│   │   └── settings_screen.dart
│   │
│   ├── user
│   │   ├── user_dashboard_screen.dart
│   │   ├── user_schedule_screen.dart
│   │   ├── user_ticketing_screen.dart
│   │   └── view_events_screen.dart
│
├── components
│   ├── custom_button.dart
│   ├── custom_text_field.dart
│   ├── event_card.dart
│   └── ticket_card.dart
│
├── routes.dart
├── main.dart

