# AI Image Studio — Android MVP

This is the first Android UI prototype for a private text-to-image application.

## Current state
- Kotlin
- Jetpack Compose
- Prompt field
- Negative prompt
- Basic generation controls
- Generate button placeholder

## Important
The iQOO Z7 uses a MediaTek Dimensity 920 and Mali-G68 MC4. The next engineering step is to benchmark a small, quantized image-generation model on the actual phone before choosing the inference runtime.

Do not assume a large desktop diffusion model will run well on this device.

## Open in Android Studio
1. Extract the project.
2. Open the extracted folder in Android Studio.
3. Let Gradle sync.
4. Enable USB debugging on the phone.
5. Connect the iQOO Z7.
6. Run the `app` configuration.

## Next step
Implement the inference layer behind the Generate button, then add local image storage and gallery.
