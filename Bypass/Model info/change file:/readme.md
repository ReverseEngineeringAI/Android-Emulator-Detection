# in file: /system/vendor/build.prop

interesting lines:
```
ro.product.vendor.device=emulator64_x86_64_arm64
ro.product.vendor.manufacturer=Google
ro.product.vendor.model=sdk_gphone64_x86_64
ro.product.vendor.name=sdk_gphone64_x86_64

ro.vendor.build.fingerprint=google/sdk_gphone64_x86_64/emulator64_x86_64_arm64:12/SE1A.220826.008/10564458:userdebug/dev-keys

ro.vendor.build.tags=dev-keys
ro.vendor.build.type=userdebug

# from out/target/product/emulator64_x86_64_arm64/obj/ETC/android_info_prop_intermediates/android_info.prop

ro.product.debugfs_restrictions.enabled=true

ro.product.board=goldfish_x86_64

# from variable PRODUCT_PROPERTY_OVERRIDES
vendor.rild.libpath=/vendor/lib64/libgoldfish-ril.so

# end of file
emulator64_x86_64_arm64:/system/vendor
```

note: '[goldfish_x86_64](https://www.google.com/search?q=goldfish_x86_64)' Goldfish kernel is known to be used in Emulators only!
