终于编译成功了：编译命令
 bazel build -c opt --config=android_arm64 mediapipe/examples/android/src/java/com/google/mediapipe/apps/handtrackinggpu:handtrackinggpu --verbose_failures --define=android_dexmerger_tool=d8_dexmerger --define=android_incremental_dexing_tool=d8_dexbuilder --nouse_workers_with_dexbuilder  --linkopt="-s"
 
 
 
 bazel build --define MEDIAPIPE_DISABLE_GPU=1 --copt -DMESA_EGL_NO_X11_HEADERS --copt -DEGL_NO_X11 mediapipe/examples/desktop/face_detection:face_detection_cpu

