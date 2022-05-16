终于编译成功了：编译命令
 bazel build -c opt --config=android_arm64 mediapipe/examples/android/src/java/com/google/mediapipe/apps/handtrackinggpu:handtrackinggpu --verbose_failures --define=android_dexmerger_tool=d8_dexmerger --define=android_incremental_dexing_tool=d8_dexbuilder --nouse_workers_with_dexbuilder  --linkopt="-s"

