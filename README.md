# AssetsCopier
since we can not use the file's absolute path in C++(JNI) code when we develop the android applications. So  we copy the files 
of assets to the SdCard. Thus we can read file by the absolute path.
we can use the AssetsCopier's static function :public  static void copyAllAssets(Context context,String destination).
Basic usage like:
AssetsCopier.copyAllAssets(this.getApplicationContext(),this.getExternalFilesDir(null).getAbsolutePath());
Note:
please replace 'package com.hqh.utils;' with your package name.
