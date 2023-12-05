# LEDE_quectel_SRPD_PCIE

issue  https://github.com/coolsnowwolf/lede/issues/11686
       https://github.com/coolsnowwolf/lede/issues/10978

`sipa_dummy.c` 和 `sipa_eth.c` 放入 `lede/package/wwan/driver/quectel_SRPD_PCIE/src/sipa`

`sbuf.c` 放入 `lede/package/wwan/driver/quectel_SRPD_PCIE/src/sipc`

`872-export-some-functions-of-the-sched-module.patch` 按照對應的內核版本放入 `lede/target/linux` 中的你要編譯的目標對應內核版本的 `patches`
