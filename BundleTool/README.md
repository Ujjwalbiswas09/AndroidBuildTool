
To Use bundletool, your device must have android 8/8.1 or Higher
Before you build aab you need to Module.zip

Here, The Command or Way to Use it.

List<String> cmd = new ArrayList<>();

cmd.add("dalvikvm");
cmd.add("-Djava.io.tmpdir="+getCacheDir()); //specify tmp directory.
cmd.add("-cp");
cmd.add("bundle-android.jar");//bundle tool.jar path.
cmd.add("com.android.tools.build.bundletool.BundleToolMain");
cmd.add("build-bundle");
cmd.add("--modules="+modulepath); //Module.zip path.
cmd.add("--output="+aab-output-path); //App.aab path.
