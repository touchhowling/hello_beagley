Clone this in ti-processor-sdk-rtos-j722s-evm-09_02_00_05/mcu_plus_sdk_j722s_09_02_00_59/examples
Download https://www.ti.com/tool/download/SYSCONFIG and https://www.ti.com/tool/PROCESSOR-SDK-J722S and https://www.ti.com/tool/C7000-CGT
export CG_TOOL_ROOT=${HOME}/ti/ti-cgt-c7000_4.1.0.LTS
export SDK_INSTALL_PATH=${HOME}/ti/ti-processor-sdk-rtos-j722s-evm-09_02_00_05/mcu_plus_sdk_j722s_09_02_00_59/
make -s -C examples/hello_world/j722s-evm/main-r5fss0–0_freertos/ti-arm-clang/
make -s -C examples/hello_world/j722s-evm/c75ss0-0_freertos/ti-c7000
make -s -C examples/hello_world/j722s-evm/c75ss1-0_freertos/ti-c7000
