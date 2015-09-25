# AssetsCopier
since we can not use the file's absolute path in C++(JNI) code when we develop the android applications. So  we copy the files\n
of assets to the SdCard. Thus we can read file by the absolute path.\n
we can use the AssetsCopier's static function :public  static void copyAllAssets(Context context,String destination).\n
Basic usage like:\n
AssetsCopier.copyAllAssets(this.getApplicationContext(),this.getExternalFilesDir(null).getAbsolutePath());\n
Note:\n
please replace 'package com.hqh.utils;' with your package name.\n
