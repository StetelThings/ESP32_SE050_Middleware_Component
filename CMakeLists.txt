#for Plug & Trust 2.16.00

set(COMPONENT_SRCDIRS   "simw-top/hostlib/hostLib/se05x/src"
                        "simw-top/hostlib/hostLib/se05x_03_xx_xx"
                        "simw-top/sss/src"
                        "simw-top/sss/src/se05x"
                        "."
                        )


set(COMPONENT_SRCS      "${COMPONENT_DIR}/simw-top/hostlib/hostLib/inc/se05x_const.h"
                        "${COMPONENT_DIR}/simw-top/hostlib/hostLib/inc/se05x_ecc_curves.h"
                        "${COMPONENT_DIR}/simw-top/hostlib/hostLib/inc/se05x_ecc_curves_inc.h"
                        "${COMPONENT_DIR}/simw-top/hostlib/hostLib/inc/se05x_ecc_curves_values.h"
                        "${COMPONENT_DIR}/simw-top/hostlib/hostLib/inc/se05x_enums.h"
                        "${COMPONENT_DIR}/simw-top/hostlib/hostLib/inc/se05x_ftr.h"
                        "${COMPONENT_DIR}/simw-top/hostlib/hostLib/inc/se05x_tlv.h"
                        "${COMPONENT_DIR}/simw-top/hostlib/hostLib/libCommon/smCom/smCom.c"
                        "${COMPONENT_DIR}/simw-top/hostlib/hostLib/libCommon/smCom/smCom.h"
                        "${COMPONENT_DIR}/simw-top/hostlib/hostLib/libCommon/smCom/smComT1oI2C.h"
                        "${COMPONENT_DIR}/simw-top/hostlib/hostLib/libCommon/smCom/smComT1oI2C.c"
                        "${COMPONENT_DIR}/simw-top/hostlib/hostLib/libCommon/smCom/T1oI2C/phEseStatus.h"
                        "${COMPONENT_DIR}/simw-top/hostlib/hostLib/libCommon/smCom/T1oI2C/phEseTypes.h"
                        "${COMPONENT_DIR}/simw-top/hostlib/hostLib/libCommon/smCom/T1oI2C/phNxpEse_Api.c"
                        "${COMPONENT_DIR}/simw-top/hostlib/hostLib/libCommon/smCom/T1oI2C/phNxpEse_Api.h"
                        "${COMPONENT_DIR}/simw-top/hostlib/hostLib/libCommon/smCom/T1oI2C/phNxpEse_Internal.h"
                        "${COMPONENT_DIR}/simw-top/hostlib/hostLib/libCommon/smCom/T1oI2C/phNxpEsePal_i2c.h"
                        "${COMPONENT_DIR}/simw-top/hostlib/hostLib/libCommon/smCom/T1oI2C/phNxpEsePal_i2c.c"
                        "${COMPONENT_DIR}/simw-top/hostlib/hostLib/libCommon/smCom/T1oI2C/phNxpEseProto7816_3.h"
                        "${COMPONENT_DIR}/simw-top/hostlib/hostLib/libCommon/smCom/T1oI2C/phNxpEseProto7816_3.c"
                        "${COMPONENT_DIR}/simw-top/hostlib/hostLib/libCommon/scp/scp.c"
                        "${COMPONENT_DIR}/simw-top/hostlib/hostLib/libCommon/infra/app_boot_nfc.c"
                        "${COMPONENT_DIR}/simw-top/hostlib/hostLib/libCommon/infra/global_platf.h"
                        "${COMPONENT_DIR}/simw-top/hostlib/hostLib/libCommon/infra/global_platf.c"
                        "${COMPONENT_DIR}/simw-top/hostlib/hostLib/libCommon/infra/sm_apdu.c"
                        "${COMPONENT_DIR}/simw-top/hostlib/hostLib/libCommon/infra/sm_apdu.h"
                        "${COMPONENT_DIR}/simw-top/hostlib/hostLib/libCommon/infra/sm_app_boot.c"
                        "${COMPONENT_DIR}/simw-top/hostlib/hostLib/libCommon/infra/sm_connect.c"
                        "${COMPONENT_DIR}/simw-top/hostlib/hostLib/libCommon/infra/sm_errors.c"
                        "${COMPONENT_DIR}/simw-top/hostlib/hostLib/libCommon/infra/sm_errors.h"
                        "${COMPONENT_DIR}/simw-top/hostlib/hostLib/libCommon/infra/sm_printf.c"
                        "${COMPONENT_DIR}/simw-top/hostlib/hostLib/libCommon/log/nxLog.c"
                        "${COMPONENT_DIR}/simw-top/hostlib/hostLib/libCommon/log/nxLog.h"
                        "${COMPONENT_DIR}/simw-top/hostlib/hostLib/libCommon/log/nxLog_App.h"
                        "${COMPONENT_DIR}/simw-top/hostlib/hostLib/libCommon/log/nxLog_DefaultConfig.h"
                        "${COMPONENT_DIR}/simw-top/hostlib/hostLib/libCommon/log/nxLog_hostLib.h"
                        "${COMPONENT_DIR}/simw-top/hostlib/hostLib/libCommon/log/nxLog_mbedtls.h"
                        "${COMPONENT_DIR}/simw-top/hostlib/hostLib/libCommon/log/nxLog_scp.h"
                        "${COMPONENT_DIR}/simw-top/hostlib/hostLib/libCommon/log/nxLog_smCom.h"
                        "${COMPONENT_DIR}/simw-top/hostlib/hostLib/libCommon/log/nxLog_sscp.h"
                        "${COMPONENT_DIR}/simw-top/hostlib/hostLib/libCommon/log/nxLog_sss.h"
                        "${COMPONENT_DIR}/simw-top/hostlib/hostLib/libCommon/log/nxLog_UseCases.h"
                        "${COMPONENT_DIR}/simw-top/hostlib/hostLib/libCommon/nxScp/nxScp03_Com.c"
                        "${COMPONENT_DIR}/simw-top/hostlib/hostLib/inc/nxScp03_Apis.h"
                        "${COMPONENT_DIR}/simw-top/hostlib/hostLib/inc/nxScp03_Const.h"
                        "${COMPONENT_DIR}/simw-top/hostlib/hostLib/inc/nxScp03_Types.h"
                        "${COMPONENT_DIR}/simw-top/sss/src/sscp/fsl_sss_sscp.c"
                        "${COMPONENT_DIR}/simw-top/sss/src/mbedtls/fsl_sss_mbedtls_apis.c"
                        "${COMPONENT_DIR}/simw-top/sss/ex/src/ex_sss_boot.c"
                        "${COMPONENT_DIR}/simw-top/sss/ex/src/ex_sss_boot_connectstring.c"
                        "${COMPONENT_DIR}/simw-top/sss/ex/src/ex_sss_se05x.c"
                        "${COMPONENT_DIR}/simw-top/sss/ex/src/ex_sss_se05x_auth.c"
                        "${COMPONENT_DIR}/simw-top/sss/ex/src/ex_sss_boot_sw.c"
                        "${COMPONENT_DIR}/simw-top/sss/ex/src/ex_sss_scp03_auth.c"
                        "${COMPONENT_DIR}/simw-top/sss/ex/src/ex_sss_se.c"
                        "${COMPONENT_DIR}/simw-top/sss/ex/src/ex_sss_se_auth.c"
                        "${COMPONENT_DIR}/simw-top/sss/ex/src/ex_sss_boot_sw.c"
                        "${COMPONENT_DIR}/simw-top/sss/src/keystore/keystore_cmn.c"
                        "${COMPONENT_DIR}/simw-top/sss/src/keystore/keystore_pc.c"
                        "${COMPONENT_DIR}/i2c_esp32.c"
                        )


set(COMPONENT_INCLUDEDIRS   
                            "."
                            "simw-top/hostlib/hostLib/inc"
                            "simw-top/hostlib/hostLib/platform/inc"
                            "simw-top/hostlib/hostLib/libCommon/infra"
                            "simw-top/hostlib/hostLib/libCommon/log"
                            "simw-top/hostlib/hostLib/libCommon/hostCrypto"
                            "simw-top/hostlib/hostLib/libCommon/smCom"
                            "simw-top/hostlib/hostLib/libCommon/smCom/T1oI2C"
                            "simw-top/hostlib/hostLib/se05x_03_xx_xx"
                            "simw-top/hostlib/hostLib/tstUtil"
                            "simw-top/hostlib/useCase/common"
                            "simw-top/sss/inc"
                            "simw-top/sss/ex/inc"
                            "simw-top/sss/ex/src"
                            #"simw-top/sss/port/default"
                            "simw-top/sss/plugin/mbedtls"
                            # ---> !!!!CHANGE WITH RELATIVE PATH!!!! <---
                            "C:/Users/Alessandro/esp/esp-idf/components/freertos/include/freertos"
                            )

set(COMPONENT_REQUIRES      "mbedtls" "freertos" "driver")

set(COMPONENT_EXCLUDE_SRCS  
                            "simw-top/sss/ex/inc/ex_sss_auth.h"
                            "simw-top/sss/ex/inc/ex_scp03_puf.h"
                            "simw-top/sss/inc/fsl_sss_ftr_default.h"
                            )

set(COMPONENT_CFLAGS 
                        "ESP32"
                        "SE05X_C"
                        "T1oI2C"
                        "T1oI2C_UM11225"
                        "SSS_USE_FTR_FILE"
                        "USE_RTOS"
                        "SDK_OS_FREE_RTOS"
                        "FSL_RTOS_FREE_RTOS"
                        "SE05X_Auth=PlatfSCP03"
                        "EXFL_SE050_AUTH_PlatfSCP03"
                        )

idf_component_register(
    SRC_DIRS "${COMPONENT_SRCDIRS}" 
    INCLUDE_DIRS "${COMPONENT_INCLUDEDIRS}" 
    REQUIRES "${COMPONENT_REQUIRES}" 
    EXCLUDE_SRCS "i2c_esp32.c" "${COMPONENT_EXCLUDE_SRCS}"
    )

idf_component_get_property(mbedtls_dir mbedtls COMPONENT_DIR)

target_sources(${COMPONENT_LIB} PRIVATE ${COMPONENT_SRCS})
target_compile_definitions(${COMPONENT_LIB} PRIVATE ${COMPONENT_CFLAGS})
target_compile_options(${COMPONENT_LIB} PRIVATE -Wno-unused-variable -Wno-format-truncation -DMBEDTLS_CONFIG_FILE="mbedtls/esp_config.h" -I${mbedtls_dir}/mbedtls/port/include -I${mbedtls_dir}/mbedtls/mbedtls/include -I${mbedtls_dir}/mbedtls/mbedtls/include/mbedtls)

idf_component_get_property(freertos_dir freertos COMPONENT_DIR)
set_source_files_properties(simw-top/hostlib/hostLib/libCommon/smCom/T1oI2C/phNxpEse_Api.c PROPERTIES COMPILE_FLAGS -I${freertos_dir}/include/freertos)

#Define the following to activate debug messages
#ADD_DEFINITIONS(-DFLOW_VERBOSE)

# Turn off some warnings for some files that have been checked
#set_source_files_properties(hal_esp32_i2c.c PROPERTIES COMPILE_FLAGS "-Wno-unused-variable -Wno-unused-but-set-variable")
#set_source_files_properties(${SE050_DIR}/basic/atca_helpers.c PROPERTIES COMPILE_FLAGS "-Wno-type-limits")
#set_source_files_properties(${SE050_DIR}/crypto/hashes/sha1_routines.c PROPERTIES COMPILE_FLAGS "-Wno-strict-aliasing")
