# AssetsCopier
since we can not use the file's absolute path in C++(JNI) code when we develop the android applications. So  we copy the files
of assets to the SdCard. Thus we can read file by the absolute path.<br>
we can use the AssetsCopier's static function :public  static void copyAllAssets(Context context,String destination)<br>
Basic usage like:<br>
AssetsCopier.copyAllAssets(this.getApplicationContext(),this.getExternalFilesDir(null).getAbsolutePath());<br>
Note:<br>
please replace 'package com.hqh.utils;' with your package name.
