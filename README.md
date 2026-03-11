# native-commands
# a) Local build command
    npx expo prebuild
    ./gradlew assembleRelease

# eas login commands
    eas login
    eas whoami
    eas logout

# Build from eas
        eas build -p android --profile preview

        eas build --profile development --platform android

        eas build -p android --profile production

        eas build -p ios --profile production
