# デバッグオプション一覧
作成中。  
順次列挙予定。

### TVP\_TEXT\_READ\_ANSI\_MBCS
テキストをShift_JISとして読み込みます。
デフォルトは未定義でUTF-8として読み込まれます。

### TVP\_TOUCH\_DISABLE
Window.enableTouchをfalseとします。
デフォルトは未定義でタッチデバイスがありマルチタッチが有効な環境では、trueとなります。

### TVP_START_UP_SCRIPT_NAME
初期読み込みスクリプト名を指定します。
デフォルトは未定義でstartup.tjsを読み込みます。

### TJS\_64BIT\_OS
64bit環境かどうかを切り分けるために内部で使用されています。

### ENABLE_DEBUGGER
デバッギ機能を持つかどうかを指定します。
デバッガを使ってデバッグする時に有効にしてビルドします。

    // 以下未整理
    TJS_TEXT_OUT_CRLF
    TJS_SUPPORT_VCL
    TJS_HOST_IS_BIG_ENDIAN
    TJS_DEBUG_DUMP_STRING
    TJS_DEBUG_TRACE
    TJS_DEBUG_PROFILE_TIMETJS_DEBUG_UNRELEASED_STRING
    TJS_DEBUG_CHECK_STRING_HEAP_INTEGRITY
    TJS_DEBUG_CHECK_STRING_HEAP_INTEGRITY
    TJS_HS_DEBUG_CHAIN
    TJS_STRICT_ERROR_CODE_CHECK
    TJS_NO_REGEXP
    TJS_VS_USE_SYSTEM_NEW
    TJS_NO_CONSTANT_FOLDING
    TJS_NO_MASK_MATHERR
    TJS_WITH_IS_NOT_RESERVED_WORD
    TVP_ENABLE_EXECUTE_AT_EXCEPTION
    TVP_NO_CHECK_WIDE_CHAR_SIZE
    TVP_SUPPORT_KPI
    TVP_SUPPORT_OLD_WAVEUNPACKER
    TVP_REPORT_HW_EXCEPTION
    TVP_DISABLE_SELECT_XP3_OR_FOLDER
    TVP_IGNORE_LOAD_TPM_PLUGIN
    TVP_LOG_TO_COMMANDLINE_CONSOLE
    TVP_IN_LOOP_TUNER
    TVP_IN_PLUGIN_STUB
    TVP_FORCE_BILINEAR
    TVP_TRANS_SHOW_FPS
    
    // 以下リリースビルド時有効なもの
    TJS_TEXT_OUT_CRLF
    TJS_JP_LOCALIZED
    TJS_DEBUG_DUMP_STRING
    TVP_LOG_TO_COMMANDLINE_CONSOLE
    DISABLE_EMBEDDED_GAME_PAD
    TVP_REPORT_HW_EXCEPTION
    TVP_ENABLE_EXECUTE_AT_EXCEPTION