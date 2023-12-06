
## 2to3

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 26.51% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 3.67% | `python` | `gc_collect_main` | gc |
| 2.91% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 2.73% | `python` | `_PyObject_Malloc` | memory |
| 2.14% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 1.96% | `python` | `_PyObject_Free` | memory |
| 1.67% | `python` | `_Py_dict_lookup` | lookup |
| 1.63% | `python` | `tupledealloc` | memory |
| 1.55% | `python` | `visit_decref` | gc |
| 1.53% | `python` | `_PyType_Lookup` | lookup |
| 1.42% | `python` | `sre_ucs1_match` | library |
| 1.32% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.09% | `python` | `visit_reachable` | gc |
| 0.93% | `python` | `PyObject_GenericGetAttr` | dynamic |
| 0.75% | `python` | `_PyPegen_is_memoized` | unknown |
| 0.70% | `python` | `initialize_locals` | interpreter |
| 0.68% | `python` | `r_object` | unknown |
| 0.67% | `libc-2.31.so` | `pthread_attr_setschedparam` | libc |
| 0.58% | `python` | `PyObject_RichCompareBool` | dynamic |
| 0.56% | `python` | `tuple_alloc` | memory |
| 0.55% | `python` | `_PyTuple_FromArraySteal` | tuple |
| 0.53% | `python` | `update_one_slot` | unknown |
| 0.51% | `python` | `PyObject_GetAttr` | dynamic |
| 0.51% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.51% | `python` | `siphash13` | str |
| 0.50% | `python` | `_PyObject_GetInstanceAttribute` | dynamic |

## aiohttp

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 25.77% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 2.47% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 2.29% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 2.03% | `python` | `_PyObject_Malloc` | memory |
| 1.87% | `python` | `_PyObject_Free` | memory |
| 1.60% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.52% | `python` | `initialize_locals` | interpreter |
| 1.39% | `python` | `gc_collect_main` | gc |
| 1.16% | `python` | `_Py_dict_lookup` | lookup |
| 1.15% | `python` | `tupledealloc` | memory |
| 1.00% | `python` | `_PyType_Lookup` | lookup |
| 0.80% | `python` | `visit_decref` | gc |
| 0.76% | `libc-2.31.so` | `pthread_attr_setschedparam` | libc |
| 0.69% | `python` | `advance` | interpreter |
| 0.57% | `python` | `siphash13` | str |
| 0.55% | `python` | `PyObject_GenericGetAttr` | dynamic |
| 0.52% | `python` | `sre_ucs1_match` | library |
| 0.51% | `python` | `_PyFunction_Vectorcall` | unknown |

## async_generators

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 22.14% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 8.75% | `python` | `_PyErr_SetObject.part.0` | unknown |
| 3.35% | `python` | `_PyObject_Free` | memory |
| 3.08% | `python` | `_PyObject_Malloc` | memory |
| 2.90% | `python` | `async_gen_asend_iternext` | unknown |
| 2.44% | `python` | `PyType_GenericAlloc` | memory |
| 2.24% | `python` | `gc_collect_main` | gc |
| 2.17% | `python` | `tupledealloc` | memory |
| 2.01% | `python` | `StopIteration_init` | unknown |
| 1.79% | `python` | `PyErr_ExceptionMatches` | unknown |
| 1.65% | `python` | `_Py_NewReference` | memory |
| 1.58% | `python` | `StopIteration_dealloc` | memory |
| 1.55% | `python` | `async_gen_wrapped_val_dealloc` | memory |
| 1.45% | `python` | `_PyTuple_FromArray` | tuple |
| 1.44% | `python` | `_PyGen_FetchStopIterationValue` | unknown |
| 1.43% | `python` | `async_gen_anext` | unknown |
| 1.42% | `python` | `_PyObject_MakeTpCall` | dynamic |
| 1.42% | `python` | `_PyAsyncGenValueWrapperNew` | memory |
| 1.38% | `python` | `async_gen_asend_dealloc` | memory |
| 1.30% | `python` | `_PyErr_ExceptionMatches (inlined)` | unknown |
| 1.26% | `python` | `tuple_alloc` | memory |
| 1.12% | `python` | `PyObject_CallOneArg` | dynamic |
| 1.12% | `python` | `_PyErr_Restore` | unknown |
| 1.08% | `python` | `type_call` | dynamic |
| 1.05% | `python` | `PyObject_GC_Del` | gc |
| 1.01% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.93% | `python` | `_PyGen_SetStopIterationValue` | unknown |
| 0.83% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 0.82% | `python` | `visit_reachable` | gc |
| 0.80% | `python` | `visit_decref` | gc |
| 0.71% | `python` | `_Py_Dealloc` | memory |
| 0.71% | `python` | `PyType_IsSubtype` | dynamic |
| 0.67% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 0.64% | `python` | `BaseException_new` | memory |
| 0.61% | `python` | `_PyTrash_end` | gc |
| 0.60% | `python` | `PyObject_CallFinalizerFromDealloc` | memory |
| 0.58% | `python` | `_PyObject_GC_Link` | gc |
| 0.57% | `python` | `_PyErr_CreateException` | unknown |
| 0.55% | `python` | `PyObject_RichCompareBool` | dynamic |
| 0.54% | `python` | `initialize_locals` | interpreter |

## async_tree

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 21.18% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 19.46% | `python` | `gc_collect_main` | gc |
| 6.02% | `python` | `visit_reachable` | gc |
| 5.77% | `python` | `visit_decref` | gc |
| 2.70% | `python` | `_PyObject_Malloc` | memory |
| 1.71% | `python` | `_PyObject_Free` | memory |
| 1.35% | `python` | `initialize_locals` | interpreter |
| 1.26% | `python` | `subtype_traverse` | gc |
| 1.17% | `python` | `_PyType_Lookup` | lookup |
| 1.16% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.08% | `python` | `_Py_dict_lookup` | lookup |
| 1.05% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.97% | `python` | `_PyObject_GetMethod` | dynamic |
| 0.79% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 0.79% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.75% | `python` | `tupledealloc` | memory |
| 0.63% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.62% | `_asyncio.cpython-313-x86_64-linux-gnu.so` | `TaskObj_traverse` | library |
| 0.59% | `python` | `context_tp_dealloc` | memory |
| 0.54% | `python` | `_PyEval_FrameClearAndPop` | unknown |
| 0.50% | `python` | `subtype_dealloc` | memory |

## async_tree_cpu_io_mixed

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 16.00% | `python` | `k_mul` | int |
| 15.97% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 14.78% | `python` | `gc_collect_main` | gc |
| 4.58% | `python` | `visit_reachable` | gc |
| 4.53% | `python` | `visit_decref` | gc |
| 3.50% | `python` | `_PyObject_Malloc` | memory |
| 2.67% | `python` | `_PyObject_Free` | memory |
| 1.75% | `python` | `PyErr_CheckSignals` | unknown |
| 1.06% | `python` | `subtype_traverse` | gc |
| 0.97% | `math.cpython-313-x86_64-linux-gnu.so` | `factorial_partial_product` | library |
| 0.90% | `python` | `initialize_locals` | interpreter |
| 0.87% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 0.80% | `python` | `_PyType_Lookup` | lookup |
| 0.78% | `python` | `_Py_dict_lookup` | lookup |
| 0.78% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 0.72% | `python` | `_PyLong_New` | memory |
| 0.71% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.67% | `python` | `_PyObject_GetMethod` | dynamic |
| 0.62% | `python` | `PyThread_get_thread_ident` | unknown |
| 0.54% | `python` | `PyObject_GC_UnTrack` | gc |

## async_tree_cpu_io_mixed_tg

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 18.26% | `python` | `gc_collect_main` | gc |
| 15.51% | `python` | `k_mul` | int |
| 14.44% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 5.10% | `python` | `visit_reachable` | gc |
| 4.81% | `python` | `visit_decref` | gc |
| 3.51% | `python` | `_PyObject_Malloc` | memory |
| 2.61% | `python` | `_PyObject_Free` | memory |
| 1.65% | `python` | `PyErr_CheckSignals` | unknown |
| 1.01% | `python` | `subtype_traverse` | gc |
| 0.90% | `math.cpython-313-x86_64-linux-gnu.so` | `factorial_partial_product` | library |
| 0.88% | `python` | `initialize_locals` | interpreter |
| 0.85% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 0.76% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 0.71% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.70% | `python` | `_PyLong_New` | memory |
| 0.65% | `python` | `_PyType_Lookup` | lookup |
| 0.63% | `python` | `set_traverse` | gc |
| 0.62% | `python` | `_PyObject_GetMethod` | dynamic |
| 0.61% | `python` | `PyThread_get_thread_ident` | unknown |
| 0.61% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.59% | `python` | `_Py_dict_lookup` | lookup |

## async_tree_io

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 29.30% | `python` | `gc_collect_main` | gc |
| 18.38% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 8.24% | `python` | `visit_reachable` | gc |
| 7.51% | `python` | `visit_decref` | gc |
| 2.00% | `python` | `_PyObject_Malloc` | memory |
| 1.49% | `python` | `subtype_traverse` | gc |
| 1.21% | `python` | `initialize_locals` | interpreter |
| 1.21% | `python` | `_PyObject_Free` | memory |
| 1.02% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 0.79% | `python` | `_PyType_Lookup` | lookup |
| 0.75% | `python` | `_PyFrame_Traverse` | unknown |
| 0.64% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.63% | `python` | `gen_traverse` | gc |
| 0.62% | `python` | `_Py_dict_lookup` | lookup |
| 0.58% | `python` | `_PyEval_Vector` | interpreter |
| 0.57% | `python` | `_PyObject_GetMethod` | dynamic |
| 0.57% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 0.55% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.51% | `_asyncio.cpython-313-x86_64-linux-gnu.so` | `TaskObj_traverse` | library |
| 0.51% | `python` | `PyObject_GC_UnTrack` | gc |

## async_tree_io_tg

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 32.11% | `python` | `gc_collect_main` | gc |
| 16.94% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 8.44% | `python` | `visit_reachable` | gc |
| 7.52% | `python` | `visit_decref` | gc |
| 1.83% | `python` | `_PyObject_Malloc` | memory |
| 1.43% | `python` | `subtype_traverse` | gc |
| 1.16% | `python` | `_PyObject_Free` | memory |
| 1.15% | `python` | `initialize_locals` | interpreter |
| 0.96% | `python` | `_PyFrame_Traverse` | unknown |
| 0.93% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 0.82% | `python` | `gen_traverse` | gc |
| 0.70% | `python` | `_PyEval_Vector` | interpreter |
| 0.65% | `python` | `_PyType_Lookup` | lookup |
| 0.64% | `python` | `set_traverse` | gc |
| 0.61% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.58% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 0.58% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.52% | `python` | `_Py_dict_lookup` | lookup |
| 0.51% | `python` | `_PyObject_GetMethod` | dynamic |
| 0.51% | `python` | `PyObject_GC_UnTrack` | gc |

## async_tree_memoization

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 21.85% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 20.56% | `python` | `gc_collect_main` | gc |
| 6.32% | `python` | `visit_decref` | gc |
| 6.30% | `python` | `visit_reachable` | gc |
| 2.52% | `python` | `_PyObject_Malloc` | memory |
| 1.53% | `python` | `subtype_traverse` | gc |
| 1.51% | `python` | `_PyObject_Free` | memory |
| 1.23% | `python` | `initialize_locals` | interpreter |
| 1.20% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.09% | `python` | `_PyType_Lookup` | lookup |
| 0.92% | `python` | `_PyObject_GetMethod` | dynamic |
| 0.89% | `python` | `_Py_dict_lookup` | lookup |
| 0.89% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.77% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.72% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 0.66% | `python` | `tupledealloc` | memory |
| 0.61% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.60% | `_asyncio.cpython-313-x86_64-linux-gnu.so` | `TaskObj_traverse` | library |
| 0.54% | `python` | `_PyEval_FrameClearAndPop` | unknown |
| 0.54% | `python` | `context_tp_dealloc` | memory |
| 0.53% | `python` | `_PyEval_Vector` | interpreter |

## async_tree_memoization_tg

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 24.81% | `python` | `gc_collect_main` | gc |
| 19.79% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 6.95% | `python` | `visit_reachable` | gc |
| 6.57% | `python` | `visit_decref` | gc |
| 2.45% | `python` | `_PyObject_Malloc` | memory |
| 1.43% | `python` | `_PyObject_Free` | memory |
| 1.36% | `python` | `subtype_traverse` | gc |
| 1.12% | `python` | `initialize_locals` | interpreter |
| 1.03% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 0.92% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.88% | `python` | `set_traverse` | gc |
| 0.88% | `python` | `_PyType_Lookup` | lookup |
| 0.83% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 0.83% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.81% | `python` | `_Py_dict_lookup` | lookup |
| 0.77% | `python` | `_PyObject_GetMethod` | dynamic |
| 0.68% | `python` | `_PyFrame_Traverse` | unknown |
| 0.61% | `python` | `PyObject_GenericGetAttr` | dynamic |
| 0.59% | `_asyncio.cpython-313-x86_64-linux-gnu.so` | `TaskObj_traverse` | library |
| 0.58% | `python` | `gen_traverse` | gc |
| 0.58% | `python` | `_PyEval_Vector` | interpreter |
| 0.57% | `python` | `tupledealloc` | memory |
| 0.54% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.50% | `python` | `_PyEval_FrameClearAndPop` | unknown |

## async_tree_tg

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 23.41% | `python` | `gc_collect_main` | gc |
| 19.20% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 6.50% | `python` | `visit_reachable` | gc |
| 6.03% | `python` | `visit_decref` | gc |
| 2.71% | `python` | `_PyObject_Malloc` | memory |
| 1.63% | `python` | `_PyObject_Free` | memory |
| 1.36% | `python` | `initialize_locals` | interpreter |
| 1.16% | `python` | `subtype_traverse` | gc |
| 1.10% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.02% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 0.95% | `python` | `set_traverse` | gc |
| 0.92% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.91% | `python` | `_PyType_Lookup` | lookup |
| 0.91% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 0.90% | `python` | `_PyObject_GetMethod` | dynamic |
| 0.70% | `python` | `_PyFrame_Traverse` | unknown |
| 0.64% | `python` | `tupledealloc` | memory |
| 0.63% | `_asyncio.cpython-313-x86_64-linux-gnu.so` | `TaskObj_traverse` | library |
| 0.61% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.56% | `python` | `gen_traverse` | gc |
| 0.56% | `python` | `PyObject_GenericGetAttr` | dynamic |
| 0.52% | `python` | `_PyEval_Vector` | interpreter |

## asyncio_tcp

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 31.34% | `[kernel.kallsyms]` | `copy_user_enhanced_fast_string` | kernel |
| 17.68% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 9.93% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 8.21% | `[kernel.kallsyms]` | `clear_page_erms` | kernel |
| 0.72% | `python` | `_PyObject_Malloc` | memory |
| 0.58% | `[kernel.kallsyms]` | `tcp_sendmsg_locked` | kernel |

## asyncio_tcp_ssl

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 38.54% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 26.15% | `libcrypto.so.1.1` | `CRYPTO_secure_actual_size` | libc |
| 11.32% | `[kernel.kallsyms]` | `copy_user_enhanced_fast_string` | kernel |
| 3.81% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 2.88% | `[kernel.kallsyms]` | `clear_page_erms` | kernel |
| 0.86% | `libssl.so.1.1` | `SSL_rstate_string` | library |
| 0.59% | `libc-2.31.so` | `pthread_attr_setschedparam` | libc |

## asyncio_websockets

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 63.92% | `libz.so.1.2.11` | `crc32_combine64` | library |
| 20.16% | `libz.so.1.2.11` | `inflateBackEnd` | library |
| 2.81% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 1.86% | `python` | `_PyEval_EvalFrameDefault` | interpreter |

## chameleon

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 36.58% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 3.73% | `python` | `_PyObject_Malloc` | memory |
| 3.28% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 2.76% | `python` | `_PyObject_Free` | memory |
| 2.06% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 2.00% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 1.87% | `python` | `_Py_dict_lookup` | lookup |
| 1.83% | `python` | `sre_ucs2_charset.isra.0` | library |
| 1.73% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 1.67% | `python` | `_PyUnicode_JoinArray.part.0` | str |
| 1.56% | `python` | `gc_collect_main` | gc |
| 1.25% | `python` | `long_to_decimal_string_internal` | int |
| 1.02% | `python` | `PyUnicode_Format` | str |
| 0.96% | `python` | `_sre_SRE_Pattern_search` | library |
| 0.90% | `python` | `insertdict` | dict |
| 0.85% | `python` | `list_append` | list |
| 0.80% | `python` | `visit_decref` | gc |
| 0.77% | `python` | `_copy_characters.part.0.constprop.0` | str |
| 0.72% | `python` | `dict_get` | dict |
| 0.68% | `python` | `resize_compact` | str |
| 0.64% | `python` | `_PyEval_FrameClearAndPop` | unknown |
| 0.60% | `python` | `visit_reachable` | gc |
| 0.55% | `python` | `PyObject_Vectorcall` | dynamic |
| 0.55% | `python` | `tupledealloc` | memory |
| 0.54% | `libc-2.31.so` | `malloc` | libc |
| 0.52% | `python` | `r_object` | unknown |
| 0.51% | `python` | `sre_search` | library |

## chaos

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 45.16% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 2.46% | `python` | `_PyObject_Free` | memory |
| 2.42% | `python` | `_PyObject_Malloc` | memory |
| 1.88% | `python` | `_PyLong_Subtract` | int |
| 1.83% | `python` | `PyType_IsSubtype` | dynamic |
| 1.75% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.26% | `python` | `_PyLong_Add` | int |
| 1.15% | `python` | `float_div` | float |
| 1.14% | `python` | `float_dealloc` | memory |
| 1.09% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 1.07% | `python` | `compute_range_length` | unknown |
| 1.05% | `python` | `gc_collect_main` | gc |
| 1.04% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.04% | `python` | `PyLong_AsDouble` | int |
| 1.03% | `python` | `float_richcompare` | float |
| 0.99% | `python` | `range_iter` | unknown |
| 0.99% | `python` | `PyFloat_FromDouble` | float |
| 0.86% | `python` | `float_sub` | float |
| 0.85% | `libm-2.31.so` | `f64xsubf128` | library |
| 0.80% | `python` | `subtype_dealloc` | memory |
| 0.75% | `python` | `_PyEval_FrameClearAndPop` | unknown |
| 0.70% | `python` | `_PyType_NewManagedObject` | memory |
| 0.70% | `python` | `_Py_NewReference` | memory |
| 0.64% | `python` | `float_pow` | float |
| 0.64% | `python` | `PyLong_FromLong` | int |
| 0.57% | `python` | `tupledealloc` | memory |
| 0.56% | `python` | `PyNumber_Subtract` | dynamic |
| 0.54% | `python` | `visit_decref` | gc |
| 0.52% | `python` | `PyNumber_TrueDivide` | dynamic |

## comprehensions

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 39.22% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 3.26% | `python` | `_PyObject_Malloc` | memory |
| 2.91% | `python` | `_PyObject_Free` | memory |
| 2.80% | `python` | `_Py_dict_lookup` | lookup |
| 2.76% | `python` | `_Py_dict_lookup` | lookup |
| 1.89% | `python` | `dict_get` | dict |
| 1.78% | `python` | `PyObject_RichCompareBool` | dynamic |
| 1.59% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.34% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 1.32% | `python` | `_PyObject_Realloc` | memory |
| 1.24% | `python` | `PyDict_GetItemRef` | dict |
| 1.18% | `python` | `list_dealloc` | memory |
| 1.07% | `python` | `gc_collect_main` | gc |
| 1.06% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.03% | `python` | `insertdict` | dict |
| 0.95% | `python` | `PyFunction_NewWithQualName` | memory |
| 0.91% | `python` | `PyObject_GC_Del` | gc |
| 0.85% | `python` | `PyObject_Hash` | dynamic |
| 0.80% | `python` | `_PyObject_GC_New` | gc |
| 0.80% | `python` | `_PyType_Lookup` | lookup |
| 0.78% | `python` | `tupledealloc` | memory |
| 0.75% | `python` | `unsafe_tuple_compare` | unknown |
| 0.73% | `python` | `long_hash` | int |
| 0.63% | `python` | `_PyList_AppendTakeRefListResize` | list |
| 0.60% | `python` | `gen_dealloc` | memory |
| 0.58% | `python` | `list_sort_impl` | list |
| 0.58% | `python` | `visit_decref` | gc |
| 0.51% | `python` | `func_dealloc` | memory |
| 0.51% | `python` | `_PyObject_GC_Link` | gc |
| 0.50% | `python` | `list_iter` | list |

## concurrent_imap

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 23.90% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 2.01% | `python` | `_PyObject_Malloc` | memory |
| 1.79% | `python` | `_PyObject_Free` | memory |
| 1.73% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.40% | `python` | `tupledealloc` | memory |
| 1.20% | `python` | `_PyType_Lookup` | lookup |
| 1.20% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.06% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 0.94% | `python` | `initialize_locals` | interpreter |
| 0.80% | `python` | `_Py_dict_lookup` | lookup |
| 0.78% | `[kernel.kallsyms]` | `zap_pte_range.isra.0` | kernel |
| 0.72% | `python` | `_PyEval_FrameClearAndPop` | unknown |
| 0.66% | `python` | `PyObject_GenericGetAttr` | dynamic |
| 0.65% | `libc-2.31.so` | `pthread_attr_setschedparam` | libc |
| 0.63% | `python` | `gc_collect_main` | gc |
| 0.57% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.54% | `python` | `subtype_dealloc` | memory |
| 0.51% | `python` | `PyObject_GetAttr` | dynamic |
| 0.51% | `[kernel.kallsyms]` | `psi_task_change` | kernel |
| 0.50% | `python` | `tuple_alloc` | memory |

## coroutines

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 43.29% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 5.14% | `python` | `gen_dealloc` | memory |
| 3.61% | `python` | `_PyObject_Malloc` | memory |
| 3.36% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 3.20% | `python` | `make_gen` | unknown |
| 2.88% | `python` | `_PyObject_Free` | memory |
| 2.60% | `python` | `_PyObject_GC_NewVar` | gc |
| 2.05% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.80% | `python` | `_PyLong_Subtract` | int |
| 1.59% | `python` | `_PyEval_FrameClearAndPop` | unknown |
| 1.47% | `python` | `_PyLong_Add` | int |
| 1.36% | `python` | `PyObject_CallFinalizerFromDealloc` | memory |
| 1.29% | `python` | `PyObject_GC_Del` | gc |
| 1.27% | `python` | `gc_collect_main` | gc |
| 1.22% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.98% | `python` | `_PyObject_GC_Link` | gc |
| 0.92% | `python` | `_PyCoro_GetAwaitableIter` | unknown |
| 0.80% | `python` | `_Py_MakeCoro` | unknown |
| 0.80% | `python` | `_PyFrame_Copy` | unknown |
| 0.69% | `python` | `visit_decref` | gc |
| 0.56% | `python` | `visit_reachable` | gc |
| 0.54% | `python` | `_Py_dict_lookup` | lookup |
| 0.53% | `python` | `_PyThreadState_PopFrame` | interpreter |

## coverage

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 15.41% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 6.43% | `python` | `call_instrumentation_vector.part.0` | unknown |
| 6.03% | `tracer.cpython-313-x86_64-linux-gnu.so` | `CTracer_trace` | library |
| 4.92% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 2.98% | `python` | `_Py_call_instrumentation_line` | unknown |
| 2.73% | `python` | `_Py_dict_lookup` | lookup |
| 2.56% | `python` | `_PyObject_Free` | memory |
| 2.46% | `python` | `siphash13` | str |
| 2.32% | `python` | `_PyObject_Malloc` | memory |
| 1.73% | `python` | `PyLong_FromLong` | int |
| 1.70% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 1.66% | `python` | `gc_collect_main` | gc |
| 1.59% | `python` | `PyDict_GetItem` | dict |
| 1.24% | `python` | `_PyObject_GenericSetAttrWithDict` | dynamic |
| 1.15% | `python` | `set_add_entry` | set |
| 0.92% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 0.89% | `python` | `visit_decref` | gc |
| 0.87% | `python` | `_PyUnicode_InternInPlace` | str |
| 0.86% | `python` | `_Py_hashtable_get_entry_generic` | unknown |
| 0.83% | `python` | `_PyType_Lookup` | lookup |
| 0.81% | `python` | `unicode_decode_utf8` | str |
| 0.79% | `python` | `PySet_Add` | unknown |
| 0.74% | `python` | `frame_dealloc` | memory |
| 0.72% | `python` | `visit_reachable` | gc |
| 0.66% | `python` | `_PyObject_GC_NewVar` | gc |
| 0.65% | `python` | `ascii_decode` | str |
| 0.60% | `python` | `PyDict_SetDefault` | dict |
| 0.60% | `python` | `PyObject_Hash` | dynamic |
| 0.59% | `python` | `_Py_call_instrumentation_jump` | unknown |
| 0.58% | `python` | `sys_trace_start` | unknown |
| 0.58% | `python` | `sys_trace_return` | unknown |
| 0.58% | `python` | `PyUnicode_New.part.0` | memory |
| 0.57% | `python` | `PyObject_GC_Del` | gc |

## crypto_pyaes

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 35.10% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 7.69% | `python` | `_PyObject_Free` | memory |
| 6.16% | `python` | `_PyObject_Malloc` | memory |
| 5.92% | `python` | `long_bitwise` | int |
| 3.12% | `python` | `long_rshift1` | int |
| 2.97% | `python` | `l_mod` | int |
| 2.52% | `python` | `_PyLong_New` | memory |
| 1.68% | `python` | `long_and` | int |
| 1.56% | `python` | `long_rshift` | int |
| 1.39% | `python` | `PyNumber_And` | dynamic |
| 1.27% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 1.11% | `python` | `long_xor` | int |
| 1.10% | `python` | `PyLong_FromLong` | int |
| 1.05% | `python` | `long_dealloc` | memory |
| 1.04% | `python` | `PyNumber_Xor` | dynamic |
| 0.97% | `python` | `gc_collect_main` | gc |
| 0.87% | `python` | `_PyLong_Add` | int |
| 0.82% | `python` | `_Py_NewReference` | memory |
| 0.81% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.79% | `python` | `PyNumber_Rshift` | dynamic |
| 0.65% | `python` | `PyNumber_Remainder` | dynamic |
| 0.53% | `python` | `long_mod` | int |
| 0.53% | `python` | `_Py_dict_lookup` | lookup |
| 0.53% | `python` | `compute_range_length` | unknown |
| 0.53% | `python` | `visit_decref` | gc |

## dask

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 14.36% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 9.94% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 5.14% | `python` | `gc_collect_main` | gc |
| 2.81% | `python` | `_PyObject_Malloc` | memory |
| 2.56% | `python` | `visit_decref` | gc |
| 2.49% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 2.24% | `python` | `_PyObject_Free` | memory |
| 1.98% | `python` | `visit_reachable` | gc |
| 1.93% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 1.46% | `python` | `tupledealloc` | memory |
| 1.40% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.32% | `python` | `_Py_dict_lookup` | lookup |
| 1.13% | `python` | `initialize_locals` | interpreter |
| 0.97% | `python` | `_PyType_Lookup` | lookup |
| 0.65% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.58% | `python` | `dict_dealloc` | memory |
| 0.56% | `libc-2.31.so` | `pthread_attr_setschedparam` | libc |
| 0.55% | `python` | `insertdict` | dict |
| 0.51% | `python` | `PyBytes_Repr` | unknown |
| 0.50% | `python` | `tuple_alloc` | memory |

## deepcopy

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 44.50% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 4.92% | `python` | `_Py_dict_lookup` | lookup |
| 3.49% | `python` | `_PyObject_Malloc` | memory |
| 3.00% | `python` | `_PyObject_Free` | memory |
| 2.97% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 2.01% | `python` | `dict_get` | dict |
| 1.22% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.10% | `python` | `_PyEval_FrameClearAndPop` | unknown |
| 1.04% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 1.00% | `python` | `sys_audit_tstate` | unknown |
| 0.83% | `python` | `_PyLong_New` | memory |
| 0.79% | `python` | `long_hash` | int |
| 0.77% | `python` | `gc_collect_main` | gc |
| 0.73% | `python` | `PyLong_FromVoidPtr` | int |
| 0.72% | `python` | `PySys_Audit` | unknown |
| 0.71% | `python` | `initialize_locals` | interpreter |
| 0.68% | `python` | `list_append` | list |
| 0.66% | `python` | `tupledealloc` | memory |
| 0.65% | `python` | `insertdict` | dict |
| 0.60% | `python` | `_PyType_Lookup` | lookup |
| 0.56% | `python` | `_PyObject_Realloc` | memory |
| 0.53% | `python` | `PyObject_Hash` | dynamic |
| 0.53% | `python` | `long_richcompare` | int |
| 0.52% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.52% | `python` | `PyObject_RichCompareBool` | dynamic |
| 0.50% | `python` | `_Py_NewReference` | memory |

## deltablue

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 56.52% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 3.25% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 2.34% | `python` | `gc_collect_main` | gc |
| 1.94% | `python` | `_PyEval_FrameClearAndPop` | unknown |
| 1.93% | `python` | `_PyObject_Malloc` | memory |
| 1.63% | `python` | `_PyObject_Free` | memory |
| 1.57% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.44% | `python` | `_PyType_Lookup` | lookup |
| 1.09% | `python` | `_PyObject_GetMethod` | dynamic |
| 1.09% | `python` | `visit_decref` | gc |
| 1.00% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 0.75% | `python` | `_PyThreadState_PopFrame` | interpreter |
| 0.73% | `python` | `visit_reachable` | gc |
| 0.59% | `python` | `_Py_dict_lookup` | lookup |

## django_template

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 33.98% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 3.33% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 2.82% | `python` | `_PyObject_Malloc (inlined)` | memory |
| 2.48% | `python` | `_PyObject_Free` | memory |
| 2.01% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.96% | `python` | `gc_collect_main` | gc |
| 1.68% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 1.52% | `python` | `_Py_dict_lookup` | lookup |
| 1.32% | `python` | `_PyType_Lookup` | lookup |
| 1.27% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 1.12% | `python` | `initialize_locals` | interpreter |
| 0.99% | `python` | `visit_decref` | gc |
| 0.91% | `python` | `tupledealloc` | memory |
| 0.76% | `python` | `replace` | str |
| 0.72% | `python` | `insertdict` | dict |
| 0.71% | `python` | `visit_reachable` | gc |
| 0.65% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.64% | `python` | `_PyObject_GC_New` | gc |
| 0.62% | `python` | `PyObject_GC_Del` | gc |
| 0.61% | `python` | `_Py_NewReference` | memory |
| 0.60% | `python` | `PyType_IsSubtype` | dynamic |
| 0.60% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.53% | `python` | `r_object` | unknown |
| 0.50% | `python` | `tuple_alloc` | memory |

## djangocms

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 17.57% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 5.74% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 4.91% | `python` | `gc_collect_main` | gc |
| 2.47% | `python` | `_PyObject_Malloc` | memory |
| 2.40% | `python` | `_Py_dict_lookup` | lookup |
| 2.05% | `python` | `visit_decref` | gc |
| 1.95% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 1.69% | `python` | `_PyType_Lookup` | lookup |
| 1.58% | `python` | `_PyObject_Free` | memory |
| 1.56% | `python` | `visit_reachable` | gc |
| 0.98% | `libc-2.31.so` | `pthread_attr_setschedparam` | libc |
| 0.91% | `python` | `PyObject_GenericGetAttr` | dynamic |
| 0.87% | `python` | `dict_traverse` | gc |
| 0.80% | `libsqlite3.so.0.8.6` | `sqlite3_exec` | library |
| 0.78% | `python` | `tupledealloc` | memory |
| 0.74% | `libz.so.1.2.11` | `inflateBackEnd` | library |
| 0.73% | `python` | `initialize_locals` | interpreter |
| 0.72% | `python` | `find_name_in_mro` | lookup |
| 0.72% | `python` | `_PyDict_GetItem_KnownHash` | dict |
| 0.66% | `python` | `advance` | interpreter |
| 0.62% | `python` | `update_one_slot` | unknown |
| 0.62% | `python` | `_PyPegen_is_memoized` | unknown |
| 0.55% | `python` | `insertdict` | dict |
| 0.52% | `python` | `_PyFrame_ClearExceptCode` | interpreter |

## docutils

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 25.15% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 6.70% | `python` | `sre_ucs1_match` | library |
| 5.98% | `python` | `gc_collect_main` | gc |
| 3.44% | `python` | `_PyObject_Malloc` | memory |
| 3.05% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 2.70% | `python` | `_PyObject_Free` | memory |
| 2.40% | `python` | `_PyType_Lookup` | lookup |
| 2.15% | `python` | `visit_decref` | gc |
| 2.02% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 1.59% | `python` | `sre_ucs2_charset.isra.0` | library |
| 1.46% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.44% | `python` | `_Py_dict_lookup` | lookup |
| 1.42% | `python` | `PyObject_GenericGetAttr` | dynamic |
| 1.32% | `python` | `visit_reachable` | gc |
| 1.26% | `python` | `list_dealloc` | memory |
| 0.87% | `python` | `tupledealloc` | memory |
| 0.79% | `python` | `_PyObject_GetInstanceAttribute` | dynamic |
| 0.75% | `python` | `PyObject_GetAttr` | dynamic |
| 0.68% | `python` | `initialize_locals` | interpreter |
| 0.63% | `libc-2.31.so` | `pthread_attr_setschedparam` | libc |
| 0.62% | `python` | `PyType_IsSubtype` | dynamic |
| 0.57% | `python` | `list_traverse` | gc |
| 0.57% | `python` | `_PyObject_GetMethod` | dynamic |
| 0.55% | `python` | `list_slice.isra.0` | list |
| 0.54% | `python` | `dict_traverse` | gc |
| 0.50% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.50% | `python` | `PyObject_GC_Del` | gc |

## dulwich_log

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 28.55% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 3.42% | `python` | `_PyObject_Malloc` | memory |
| 2.51% | `python` | `_PyObject_Free` | memory |
| 2.49% | `libz.so.1.2.11` | `inflateCodesUsed` | library |
| 2.48% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 1.58% | `libz.so.1.2.11` | `inflateBackEnd` | library |
| 1.34% | `libz.so.1.2.11` | `inflate` | library |
| 1.29% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.21% | `python` | `gc_collect_main` | gc |
| 1.19% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.03% | `python` | `tupledealloc` | memory |
| 0.71% | `libc-2.31.so` | `pthread_attr_setschedparam` | libc |
| 0.70% | `python` | `visit_decref` | gc |
| 0.69% | `python` | `_PyType_Lookup` | lookup |
| 0.54% | `python` | `initialize_locals` | interpreter |
| 0.52% | `python` | `tuple_alloc` | memory |

## fannkuch

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 36.89% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 8.32% | `python` | `PySlice_AdjustIndices` | slice |
| 5.19% | `python` | `list_ass_slice` | list |
| 5.09% | `python` | `list_subscript` | list |
| 3.71% | `python` | `list_dealloc` | memory |
| 3.22% | `python` | `_PyObject_Free` | memory |
| 3.01% | `python` | `_PyBuildSlice_ConsumeRefs` | slice |
| 2.89% | `python` | `_PyEval_SliceIndex` | slice |
| 2.41% | `python` | `slice_dealloc` | memory |
| 2.31% | `python` | `PyNumber_AsSsize_t` | dynamic |
| 2.08% | `python` | `_PyObject_Malloc` | memory |
| 1.98% | `python` | `PySlice_New` | memory |
| 1.94% | `python` | `_Py_NewReference` | memory |
| 1.94% | `python` | `_PyLong_Add` | int |
| 1.88% | `python` | `PySlice_Unpack` | slice |
| 1.45% | `python` | `list_ass_subscript` | list |
| 1.39% | `python` | `PyLong_AsSsize_t` | int |
| 0.96% | `python` | `PyObject_GetItem` | dynamic |
| 0.93% | `python` | `list_insert` | list |
| 0.69% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.63% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 0.62% | `python` | `_PyTrash_end` | gc |
| 0.61% | `python` | `PyObject_SetItem` | dynamic |
| 0.60% | `python` | `_PyLong_Subtract` | int |
| 0.55% | `python` | `list_pop` | list |
| 0.55% | `python` | `list_slice.isra.0` | list |

## float

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 36.67% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 4.14% | `libm-2.31.so` | `f64xsubf128` | library |
| 3.72% | `python` | `gc_collect_main` | gc |
| 3.23% | `python` | `_PyObject_Malloc` | memory |
| 3.07% | `python` | `subtype_traverse` | gc |
| 2.58% | `python` | `visit_reachable` | gc |
| 2.54% | `python` | `visit_decref` | gc |
| 2.04% | `python` | `_PyObject_Free` | memory |
| 1.87% | `python` | `PyFloat_FromDouble` | float |
| 1.82% | `python` | `float_div` | float |
| 1.60% | `python` | `subtype_dealloc` | memory |
| 1.46% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.31% | `python` | `float_dealloc` | memory |
| 0.96% | `python` | `PyType_IsSubtype` | dynamic |
| 0.86% | `python` | `_Py_NewReference` | memory |
| 0.85% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.83% | `python` | `initialize_locals` | interpreter |
| 0.81% | `python` | `tupledealloc` | memory |
| 0.81% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 0.71% | `python` | `_PyEval_FrameClearAndPop` | unknown |
| 0.66% | `python` | `PyType_GenericAlloc` | memory |
| 0.64% | `python` | `_PyType_Lookup` | lookup |
| 0.64% | `python` | `_Py_Dealloc` | memory |
| 0.56% | `python` | `PyNumber_InPlaceTrueDivide` | dynamic |
| 0.52% | `python` | `_PyObject_MakeTpCall` | dynamic |
| 0.52% | `python` | `long_float` | int |
| 0.51% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.50% | `python` | `PyFloat_AsDouble.part.0` | float |

## gc_collect

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 28.25% | `python` | `gc_collect_main` | gc |
| 13.82% | `python` | `visit_reachable` | gc |
| 12.83% | `python` | `visit_decref` | gc |
| 7.87% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 4.09% | `python` | `dict_traverse` | gc |
| 1.69% | `python` | `func_traverse` | gc |
| 1.68% | `python` | `PyObject_VisitManagedDict` | dynamic |
| 1.63% | `python` | `_PyDict_MaybeUntrack` | gc |
| 1.63% | `python` | `PyObject_IS_GC` | gc |
| 1.48% | `python` | `subtype_traverse` | gc |
| 1.44% | `python` | `set_traverse` | gc |
| 1.37% | `python` | `_PyObject_Malloc` | memory |
| 1.07% | `python` | `type_is_gc` | gc |
| 0.90% | `python` | `_PyObject_Free` | memory |
| 0.81% | `python` | `type_traverse` | gc |
| 0.80% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.72% | `python` | `tupletraverse` | tuple |
| 0.62% | `python` | `list_traverse` | gc |
| 0.62% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 0.55% | `libc-2.31.so` | `__nss_database_lookup` | libc |

## gc_traversal

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 29.24% | `python` | `visit_reachable` | gc |
| 19.58% | `python` | `visit_decref` | gc |
| 15.96% | `python` | `list_traverse` | gc |
| 11.16% | `python` | `gc_collect_main` | gc |
| 4.63% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 1.65% | `python` | `dict_traverse` | gc |
| 0.74% | `python` | `PyObject_IS_GC` | gc |
| 0.68% | `python` | `func_traverse` | gc |
| 0.66% | `python` | `_PyObject_Malloc` | memory |
| 0.66% | `python` | `_PyObject_Free` | memory |
| 0.63% | `python` | `_PyDict_MaybeUntrack` | gc |
| 0.59% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.57% | `python` | `set_traverse` | gc |

## generators

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 48.92% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 4.54% | `python` | `gc_collect_main` | gc |
| 3.68% | `python` | `_PyObject_Malloc` | memory |
| 2.82% | `python` | `_PyObject_Free` | memory |
| 1.52% | `python` | `visit_reachable` | gc |
| 1.42% | `python` | `visit_decref` | gc |
| 1.34% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 1.19% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.15% | `python` | `gen_dealloc` | memory |
| 1.09% | `python` | `PyObject_RichCompareBool` | dynamic |
| 1.07% | `python` | `initialize_locals` | interpreter |
| 0.93% | `python` | `long_add` | int |
| 0.87% | `python` | `PyObject_VisitManagedDict` | dynamic |
| 0.81% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.80% | `python` | `subtype_traverse` | gc |
| 0.76% | `python` | `_PyObject_GC_NewVar` | gc |
| 0.72% | `python` | `range_subscript` | unknown |
| 0.70% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.69% | `python` | `_PyEval_FrameClearAndPop` | unknown |
| 0.67% | `python` | `compute_range_length` | unknown |
| 0.64% | `python` | `_PyType_Lookup` | lookup |
| 0.62% | `python` | `make_gen` | unknown |
| 0.59% | `python` | `PyNumber_Add` | dynamic |
| 0.55% | `python` | `long_richcompare` | int |
| 0.54% | `python` | `_PyBuildSlice_ConsumeRefs` | slice |

## genshi

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 42.10% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 3.36% | `python` | `_PyObject_Malloc` | memory |
| 2.72% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 2.47% | `python` | `_PyObject_Free` | memory |
| 2.12% | `python` | `_Py_dict_lookup` | lookup |
| 1.34% | `python` | `gc_collect_main` | gc |
| 1.28% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.28% | `python` | `tupledealloc` | memory |
| 1.27% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 1.13% | `python` | `insertdict` | dict |
| 1.04% | `python` | `_PyType_Lookup` | lookup |
| 0.76% | `python` | `_PyTuple_FromArraySteal` | tuple |
| 0.71% | `libc-2.31.so` | `pthread_attr_setschedparam` | libc |
| 0.70% | `python` | `_PyDict_FromItems` | dict |
| 0.68% | `python` | `_PyObject_GC_New` | gc |
| 0.62% | `python` | `_PyObject_GetMethod` | dynamic |
| 0.59% | `python` | `PyDict_GetItemRef` | dict |
| 0.56% | `python` | `tuple_alloc` | memory |
| 0.53% | `python` | `pattern_subx` | library |
| 0.53% | `python` | `free_keys_object` | dict |
| 0.53% | `python` | `PyObject_IsTrue` | dynamic |
| 0.51% | `python` | `_PyEval_FrameClearAndPop` | unknown |

## go

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 60.50% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 2.39% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 2.36% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.96% | `python` | `_PyObject_GetMethod` | dynamic |
| 1.61% | `python` | `_PyObject_Free` | memory |
| 1.44% | `python` | `_PyObject_Malloc` | memory |
| 1.33% | `python` | `_Py_dict_lookup` | lookup |
| 1.24% | `python` | `_PyType_Lookup` | lookup |
| 1.10% | `python` | `_PyEval_FrameClearAndPop` | unknown |
| 1.05% | `python` | `gc_collect_main` | gc |
| 0.95% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 0.86% | `python` | `PyDict_GetItemRef` | dict |
| 0.71% | `python` | `long_bitwise` | int |
| 0.64% | `python` | `visit_decref` | gc |
| 0.53% | `python` | `initialize_locals` | interpreter |

## gunicorn

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 27.12% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 2.84% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 2.22% | `python` | `_PyObject_Malloc` | memory |
| 2.20% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 1.92% | `python` | `_PyObject_Free` | memory |
| 1.65% | `python` | `gc_collect_main` | gc |
| 1.53% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.37% | `python` | `initialize_locals` | interpreter |
| 1.23% | `python` | `_Py_dict_lookup` | lookup |
| 1.20% | `python` | `tupledealloc` | memory |
| 0.98% | `python` | `_PyType_Lookup` | lookup |
| 0.92% | `python` | `advance` | interpreter |
| 0.75% | `python` | `visit_decref` | gc |
| 0.68% | `libc-2.31.so` | `pthread_attr_setschedparam` | libc |
| 0.57% | `python` | `PyObject_GenericGetAttr` | dynamic |
| 0.55% | `python` | `PyObject_IsTrue` | dynamic |
| 0.55% | `python` | `tuple_alloc` | memory |
| 0.52% | `python` | `sre_ucs1_match` | library |

## hexiom

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 51.57% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 3.25% | `python` | `PyObject_RichCompareBool` | dynamic |
| 2.26% | `python` | `list_contains` | list |
| 2.10% | `python` | `long_richcompare` | int |
| 1.91% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.71% | `python` | `_PyObject_Malloc` | memory |
| 1.65% | `python` | `_PyObject_Free` | memory |
| 1.32% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.26% | `python` | `gc_collect_main` | gc |
| 1.25% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 1.20% | `python` | `gen_iternext` | unknown |
| 1.06% | `python` | `_PyEval_FrameClearAndPop` | unknown |
| 0.69% | `python` | `PyLong_FromLong` | int |
| 0.66% | `python` | `visit_decref` | gc |
| 0.64% | `python` | `_Py_dict_lookup` | lookup |
| 0.61% | `python` | `builtin_sum` | unknown |
| 0.56% | `python` | `PyLong_FromSsize_t` | int |
| 0.51% | `python` | `PySequence_Contains` | dynamic |
| 0.50% | `python` | `list_dealloc` | memory |

## html5lib

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 36.20% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 5.21% | `python` | `sre_ucs2_charset.isra.0` | library |
| 3.34% | `python` | `gc_collect_main` | gc |
| 2.58% | `python` | `_PyObject_Malloc` | memory |
| 2.24% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.96% | `python` | `_PyObject_Free` | memory |
| 1.52% | `python` | `_Py_dict_lookup` | lookup |
| 1.51% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 1.28% | `python` | `visit_decref` | gc |
| 1.25% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 0.97% | `python` | `PyDict_GetItemRef` | dict |
| 0.84% | `python` | `visit_reachable` | gc |
| 0.72% | `python` | `tupledealloc` | memory |
| 0.70% | `python` | `sre_ucs1_count` | library |
| 0.68% | `python` | `PyObject_RichCompareBool` | dynamic |
| 0.67% | `python` | `_PyType_Lookup` | lookup |
| 0.63% | `libc-2.31.so` | `pthread_attr_setschedparam` | libc |
| 0.57% | `python` | `initialize_locals` | interpreter |
| 0.56% | `python` | `PyObject_GenericGetAttr` | dynamic |
| 0.54% | `python` | `insertdict` | dict |

## json

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 12.01% | `_json.cpython-313-x86_64-linux-gnu.so` | `scanstring_unicode` | library |
| 7.64% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 6.49% | `_json.cpython-313-x86_64-linux-gnu.so` | `scan_once_unicode` | library |
| 6.00% | `python` | `_PyObject_Malloc` | memory |
| 5.31% | `python` | `siphash13` | str |
| 4.61% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 4.31% | `python` | `_PyObject_Free` | memory |
| 3.04% | `python` | `PyDict_SetDefault` | dict |
| 2.62% | `python` | `insertdict` | dict |
| 2.47% | `python` | `_Py_dict_lookup` | lookup |
| 2.32% | `python` | `PyLong_FromString` | int |
| 2.08% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 2.03% | `python` | `PyUnicode_Substring` | str |
| 2.00% | `libc-2.31.so` | `pthread_attr_setschedparam` | libc |
| 1.75% | `python` | `free_keys_object` | dict |
| 1.71% | `python` | `PyUnicode_New.part.0` | memory |
| 1.48% | `python` | `find_empty_slot` | dict |
| 1.19% | `python` | `build_indices_unicode` | dict |
| 0.92% | `python` | `PyObject_IS_GC` | gc |
| 0.88% | `python` | `PyDict_SetItem` | dict |
| 0.85% | `python` | `gc_collect_main` | gc |
| 0.74% | `python` | `_sre_SRE_Pattern_match` | library |
| 0.63% | `python` | `tupledealloc` | memory |
| 0.63% | `python` | `unicode_dealloc` | memory |
| 0.59% | `python` | `new_keys_object` | unknown |
| 0.55% | `python` | `sre_ucs1_match` | library |
| 0.55% | `python` | `_Py_NewReference` | memory |
| 0.54% | `python` | `initialize_locals` | interpreter |
| 0.54% | `python` | `_PyFrame_ClearExceptCode` | interpreter |

## json_dumps

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 13.40% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 6.76% | `python` | `_PyObject_Malloc` | memory |
| 6.41% | `_json.cpython-313-x86_64-linux-gnu.so` | `py_encode_basestring_ascii` | library |
| 4.71% | `python` | `_PyObject_Free` | memory |
| 3.54% | `python` | `_copy_characters.part.0.constprop.0` | str |
| 3.22% | `python` | `_PyUnicodeWriter_WriteStr` | str |
| 2.65% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 2.61% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 2.56% | `python` | `_Py_dict_lookup` | lookup |
| 2.48% | `_json.cpython-313-x86_64-linux-gnu.so` | `encoder_listencode_obj` | library |
| 2.19% | `python` | `resize_compact` | str |
| 1.98% | `python` | `PyUnicode_New` | memory |
| 1.77% | `python` | `vgetargskeywords.constprop.0` | unknown |
| 1.61% | `_json.cpython-313-x86_64-linux-gnu.so` | `encoder_encode_key_value` | library |
| 1.31% | `python` | `gc_collect_main` | gc |
| 1.21% | `python` | `tupledealloc` | memory |
| 1.14% | `python` | `convertitem.constprop.0` | unknown |
| 1.13% | `python` | `PyDict_GetItemRef` | dict |
| 1.01% | `python` | `PyDict_Next` | dict |
| 0.93% | `python` | `initialize_locals` | interpreter |
| 0.92% | `python` | `_PyObject_Realloc` | memory |
| 0.89% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 0.79% | `python` | `_PyUnicodeWriter_PrepareInternal` | str |
| 0.67% | `python` | `_Py_Dealloc` | memory |
| 0.64% | `python` | `long_to_decimal_string_internal` | int |
| 0.63% | `python` | `_PyType_Lookup` | lookup |
| 0.62% | `python` | `visit_decref` | gc |
| 0.60% | `python` | `_Py_NewReference` | memory |
| 0.60% | `python` | `unicode_dealloc` | memory |
| 0.52% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.52% | `python` | `long_hash` | int |

## json_loads

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 13.26% | `_json.cpython-313-x86_64-linux-gnu.so` | `scanstring_unicode` | library |
| 7.11% | `python` | `_PyObject_Malloc` | memory |
| 6.99% | `_json.cpython-313-x86_64-linux-gnu.so` | `scan_once_unicode` | library |
| 6.33% | `python` | `siphash13` | str |
| 6.31% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 5.76% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 4.96% | `python` | `_PyObject_Free` | memory |
| 3.18% | `python` | `PyUnicode_Substring` | str |
| 2.83% | `python` | `_Py_dict_lookup` | lookup |
| 2.82% | `python` | `insertdict` | dict |
| 2.49% | `python` | `PyDict_SetDefault` | dict |
| 2.49% | `python` | `PyUnicode_New.part.0` | memory |
| 2.37% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 2.24% | `python` | `PyLong_FromString` | int |
| 1.28% | `python` | `find_empty_slot` | dict |
| 0.99% | `python` | `build_indices_unicode` | dict |
| 0.92% | `libc-2.31.so` | `pthread_attr_setschedparam` | libc |
| 0.90% | `python` | `free_keys_object` | dict |
| 0.89% | `python` | `gc_collect_main` | gc |
| 0.83% | `python` | `PyDict_SetItem` | dict |
| 0.79% | `python` | `unicode_dealloc` | memory |
| 0.74% | `python` | `PyObject_IS_GC` | gc |
| 0.60% | `python` | `_Py_NewReference` | memory |
| 0.51% | `python` | `visit_decref` | gc |

## logging

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 44.32% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 3.37% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 2.22% | `python` | `initialize_locals` | interpreter |
| 2.09% | `python` | `_PyObject_Malloc` | memory |
| 1.85% | `python` | `_Py_dict_lookup` | lookup |
| 1.82% | `python` | `_PyObject_Free` | memory |
| 1.70% | `python` | `_PyEval_FrameClearAndPop` | unknown |
| 1.53% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 1.41% | `python` | `PyCode_Addr2Line` | unknown |
| 1.38% | `python` | `dict_dealloc` | memory |
| 1.32% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 1.01% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.97% | `python` | `PyDict_GetItemRef` | dict |
| 0.88% | `python` | `PyDict_New` | memory |
| 0.82% | `python` | `_PyType_Lookup` | lookup |
| 0.79% | `python` | `_Py_NewReference` | memory |
| 0.77% | `python` | `tupledealloc` | memory |
| 0.69% | `python` | `_PyTrash_end` | gc |
| 0.68% | `python` | `PyObject_GenericGetAttr` | dynamic |
| 0.65% | `python` | `_PyThreadState_PopFrame` | interpreter |
| 0.64% | `python` | `gc_collect_main` | gc |
| 0.59% | `python` | `PyUnicode_Contains` | str |
| 0.53% | `python` | `PyObject_GetAttr` | dynamic |
| 0.52% | `python` | `vgetargs1_impl` | unknown |

## mako

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 33.37% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 5.72% | `python` | `replace` | str |
| 3.48% | `python` | `_PyObject_Free` | memory |
| 3.28% | `python` | `long_to_decimal_string_internal` | int |
| 3.11% | `python` | `_PyObject_Malloc` | memory |
| 2.97% | `python` | `_PyUnicode_JoinArray.part.0` | str |
| 2.21% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 1.86% | `python` | `unicode_replace` | str |
| 1.78% | `python` | `deque_append` | unknown |
| 1.71% | `python` | `dequeiter_next` | unknown |
| 1.54% | `python` | `gc_collect_main` | gc |
| 1.49% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.86% | `python` | `list_extend` | list |
| 0.81% | `python` | `list_dealloc` | memory |
| 0.80% | `libc-2.31.so` | `pthread_attr_setschedparam` | libc |
| 0.80% | `python` | `visit_decref` | gc |
| 0.78% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 0.78% | `python` | `PyUnicode_New` | memory |
| 0.70% | `python` | `PyErr_CheckSignals` | unknown |
| 0.69% | `python` | `sre_ucs2_charset.isra.0` | library |
| 0.65% | `python` | `_Py_dict_lookup` | lookup |
| 0.65% | `python` | `deque_clear.part.0` | unknown |
| 0.62% | `python` | `PyObject_Str` | dynamic |
| 0.59% | `python` | `_PyLong_New` | memory |
| 0.59% | `python` | `visit_reachable` | gc |
| 0.51% | `[kernel.kallsyms]` | `native_irq_return_iret` | kernel |

## mdp

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 27.91% | `python` | `tuplehash` | tuple |
| 15.38% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 13.78% | `python` | `PyObject_Hash` | dynamic |
| 10.40% | `python` | `long_hash` | int |
| 5.82% | `python` | `_Py_dict_lookup` | lookup |
| 2.95% | `python` | `PyObject_RichCompareBool` | dynamic |
| 1.83% | `python` | `tuplerichcompare` | tuple |
| 1.24% | `python` | `_PyObject_Free` | memory |
| 1.18% | `python` | `_PyObject_Malloc` | memory |
| 1.14% | `python` | `dict_subscript` | dict |
| 0.92% | `python` | `_PyLong_GCD` | int |
| 0.77% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 0.72% | `python` | `PyDict_GetItemRef` | dict |
| 0.63% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 0.62% | `python` | `unicodekeys_lookup_unicode` | lookup |

## meteor_contest

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 21.68% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 7.30% | `python` | `set_issubset` | set |
| 6.70% | `python` | `set_lookkey` | set |
| 5.78% | `python` | `setiter_iternext` | set |
| 3.48% | `python` | `set_difference` | set |
| 3.24% | `python` | `set_dealloc` | memory |
| 2.64% | `python` | `PyObject_RichCompareBool` | dynamic |
| 2.50% | `python` | `_PyObject_Free` | memory |
| 2.37% | `python` | `_PyObject_Malloc` | memory |
| 1.89% | `python` | `set_add_entry` | set |
| 1.57% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 1.51% | `python` | `list_dealloc` | memory |
| 1.31% | `python` | `long_richcompare` | int |
| 1.24% | `python` | `gc_collect_main` | gc |
| 1.24% | `python` | `list_slice.isra.0` | list |
| 1.22% | `python` | `min_max` | unknown |
| 1.14% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.09% | `python` | `PyObject_RichCompare` | dynamic |
| 1.03% | `python` | `PyIter_Next` | unknown |
| 0.86% | `python` | `set_intersection` | set |
| 0.79% | `python` | `set_table_resize` | set |
| 0.69% | `python` | `set_update_internal` | set |
| 0.66% | `python` | `PyObject_GC_Del` | gc |
| 0.65% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 0.62% | `python` | `visit_decref` | gc |
| 0.61% | `python` | `PyType_GenericAlloc` | memory |
| 0.58% | `python` | `_Py_dict_lookup` | lookup |
| 0.56% | `python` | `tupledealloc` | memory |
| 0.52% | `python` | `_PyObject_GC_New` | gc |

## mypy2

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 29.91% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 13.79% | `python` | `gc_collect_main` | gc |
| 2.90% | `python` | `_PyObject_Malloc` | memory |
| 2.70% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 2.62% | `python` | `visit_decref` | gc |
| 2.27% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 2.07% | `python` | `_PyObject_Free` | memory |
| 1.56% | `python` | `_PyType_Lookup` | lookup |
| 1.55% | `python` | `initialize_locals` | interpreter |
| 1.50% | `python` | `_Py_dict_lookup` | lookup |
| 1.36% | `python` | `subtype_traverse` | gc |
| 1.36% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 1.26% | `python` | `visit_reachable` | gc |
| 1.22% | `python` | `subtype_dealloc` | memory |
| 1.08% | `python` | `PyDict_GetItemRef` | dict |
| 0.91% | `python` | `siphash13` | str |
| 0.90% | `_json.cpython-313-x86_64-linux-gnu.so` | `scanstring_unicode` | library |
| 0.81% | `_json.cpython-313-x86_64-linux-gnu.so` | `scan_once_unicode` | library |
| 0.76% | `python` | `tupledealloc` | memory |
| 0.70% | `python` | `PyType_IsSubtype` | dynamic |
| 0.70% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.68% | `python` | `list_dealloc` | memory |
| 0.58% | `python` | `_PyEval_FrameClearAndPop` | unknown |
| 0.52% | `python` | `insertdict` | dict |
| 0.52% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.51% | `python` | `list_traverse` | gc |

## nbody

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 66.42% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 5.13% | `python` | `PyFloat_FromDouble` | float |
| 3.50% | `libm-2.31.so` | `f64xsubf128` | library |
| 2.23% | `python` | `float_dealloc` | memory |
| 1.94% | `python` | `_Py_NewReference` | memory |
| 1.19% | `python` | `float_pow` | float |
| 0.88% | `python` | `gc_collect_main` | gc |
| 0.81% | `python` | `_PyObject_Malloc` | memory |
| 0.79% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.75% | `python` | `_PyObject_Free` | memory |

## nqueens

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 31.68% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 4.31% | `python` | `_PyObject_Malloc` | memory |
| 3.71% | `python` | `_PyObject_Free` | memory |
| 2.02% | `python` | `set_add_entry` | set |
| 1.93% | `python` | `gen_iternext` | unknown |
| 1.75% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 1.74% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.60% | `python` | `PySlice_AdjustIndices` | slice |
| 1.46% | `python` | `gc_collect_main` | gc |
| 1.46% | `python` | `list_dealloc` | memory |
| 1.23% | `python` | `_PyBuildSlice_ConsumeRefs` | slice |
| 1.19% | `python` | `set_dealloc` | memory |
| 0.97% | `python` | `tupledealloc` | memory |
| 0.93% | `python` | `_Py_dict_lookup` | lookup |
| 0.92% | `python` | `_Py_NewReference` | memory |
| 0.82% | `python` | `_PyLong_Add` | int |
| 0.78% | `python` | `_PyType_Lookup` | lookup |
| 0.76% | `python` | `list_subscript` | list |
| 0.76% | `python` | `visit_decref` | gc |
| 0.73% | `python` | `PyFunction_NewWithQualName` | memory |
| 0.72% | `python` | `set_update_internal` | set |
| 0.66% | `python` | `PyNumber_AsSsize_t` | dynamic |
| 0.66% | `python` | `PyLong_FromLong` | int |
| 0.65% | `python` | `set_table_resize` | set |
| 0.64% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 0.60% | `python` | `list_slice.isra.0` | list |
| 0.59% | `python` | `PyObject_GC_Del` | gc |
| 0.56% | `python` | `func_dealloc` | memory |
| 0.56% | `python` | `_PyTrash_end` | gc |
| 0.55% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.54% | `python` | `visit_reachable` | gc |
| 0.52% | `python` | `PySequence_Tuple` | dynamic |
| 0.51% | `python` | `_PyEval_SliceIndex` | slice |
| 0.50% | `python` | `PyIter_Next` | unknown |
| 0.50% | `python` | `list_ass_slice` | list |
| 0.50% | `python` | `slice_dealloc` | memory |

## pathlib

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 17.52% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 4.50% | `python` | `_PyObject_Malloc` | memory |
| 4.22% | `python` | `_PyObject_Free` | memory |
| 1.63% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.39% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 1.31% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.25% | `[kernel.kallsyms]` | `__d_lookup_rcu` | kernel |
| 1.18% | `python` | `initialize_locals` | interpreter |
| 1.17% | `libpthread-2.31.so` | `__pthread_mutex_lock` | library |
| 1.15% | `python` | `_PyType_Lookup` | lookup |
| 1.01% | `[kernel.kallsyms]` | `__ext4fs_dirhash` | kernel |
| 0.97% | `[kernel.kallsyms]` | `ext4_htree_store_dirent` | kernel |
| 0.96% | `python` | `gc_collect_main` | gc |
| 0.93% | `libpthread-2.31.so` | `pthread_mutex_unlock` | library |
| 0.91% | `[kernel.kallsyms]` | `memset_erms` | kernel |
| 0.85% | `python` | `_Py_dict_lookup` | lookup |
| 0.85% | `python` | `tupledealloc` | memory |
| 0.80% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.72% | `python` | `PyDict_GetItemRef` | dict |
| 0.68% | `python` | `_PyLong_New` | memory |
| 0.67% | `python` | `_Py_NewReference` | memory |
| 0.62% | `[kernel.kallsyms]` | `strncpy_from_user` | kernel |
| 0.62% | `python` | `sre_ucs1_match` | library |
| 0.62% | `[kernel.kallsyms]` | `filldir64` | kernel |
| 0.60% | `python` | `subtype_dealloc` | memory |
| 0.58% | `libc-2.31.so` | `pthread_attr_setschedparam` | libc |
| 0.56% | `python` | `_Py_Dealloc` | memory |
| 0.55% | `python` | `k_mul` | int |
| 0.53% | `python` | `_Py_type_getattro` | lookup |
| 0.52% | `python` | `_PyEval_FrameClearAndPop` | unknown |
| 0.51% | `python` | `list_dealloc` | memory |
| 0.51% | `python` | `visit_decref` | gc |
| 0.50% | `python` | `_PyUnicode_JoinArray.part.0` | str |

## pickle

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 23.47% | `_pickle.cpython-313-x86_64-linux-gnu.so` | `save` | library |
| 8.99% | `_pickle.cpython-313-x86_64-linux-gnu.so` | `_Pickler_Write` | library |
| 7.71% | `_pickle.cpython-313-x86_64-linux-gnu.so` | `PyMemoTable_Set` | library |
| 4.79% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 3.81% | `_pickle.cpython-313-x86_64-linux-gnu.so` | `Pickler_clear` | library |
| 3.41% | `_pickle.cpython-313-x86_64-linux-gnu.so` | `memo_put.isra.0` | library |
| 3.38% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 2.75% | `python` | `PyDict_Next` | dict |
| 2.63% | `python` | `PyUnicode_AsUTF8AndSize` | str |
| 2.49% | `_pickle.cpython-313-x86_64-linux-gnu.so` | `_Pickler_Write.constprop.3` | library |
| 1.88% | `python` | `_PyObject_Malloc` | memory |
| 1.73% | `_pickle.cpython-313-x86_64-linux-gnu.so` | `memo_get.isra.0` | library |
| 1.68% | `libc-2.31.so` | `pthread_attr_setschedparam` | libc |
| 1.57% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.41% | `python` | `_PyObject_Free` | memory |
| 1.21% | `python` | `gc_collect_main` | gc |
| 0.78% | `python` | `_Py_dict_lookup` | lookup |
| 0.67% | `python` | `_PyType_Lookup` | lookup |
| 0.58% | `python` | `visit_decref` | gc |

## pickle_dict

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 40.89% | `_pickle.cpython-313-x86_64-linux-gnu.so` | `save` | library |
| 12.14% | `python` | `PyDict_Next` | dict |
| 8.18% | `_pickle.cpython-313-x86_64-linux-gnu.so` | `_Pickler_Write` | library |
| 6.22% | `_pickle.cpython-313-x86_64-linux-gnu.so` | `_Pickler_Write.constprop.3` | library |
| 3.73% | `python` | `PyLong_AsLongAndOverflow` | int |
| 3.63% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 2.25% | `_pickle.cpython-313-x86_64-linux-gnu.so` | `PyMemoTable_Set` | library |
| 1.33% | `_pickle.cpython-313-x86_64-linux-gnu.so` | `Pickler_clear` | library |
| 1.03% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 0.90% | `python` | `gc_collect_main` | gc |
| 0.85% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.76% | `_pickle.cpython-313-x86_64-linux-gnu.so` | `0x0000000000005e94` | library |
| 0.67% | `_pickle.cpython-313-x86_64-linux-gnu.so` | `memo_put.isra.0` | library |
| 0.66% | `_pickle.cpython-313-x86_64-linux-gnu.so` | `0x0000000000005d04` | library |
| 0.56% | `python` | `_PyObject_Malloc` | memory |
| 0.52% | `libc-2.31.so` | `pthread_attr_setschedparam` | libc |

## pickle_list

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 37.37% | `_pickle.cpython-313-x86_64-linux-gnu.so` | `save` | library |
| 8.88% | `_pickle.cpython-313-x86_64-linux-gnu.so` | `_Pickler_Write` | library |
| 5.23% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 4.42% | `python` | `PyLong_AsLongAndOverflow (inlined)` | int |
| 4.01% | `_pickle.cpython-313-x86_64-linux-gnu.so` | `PyMemoTable_Set` | library |
| 3.83% | `_pickle.cpython-313-x86_64-linux-gnu.so` | `_Pickler_Write.constprop.3` | library |
| 2.04% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 1.86% | `_pickle.cpython-313-x86_64-linux-gnu.so` | `Pickler_clear` | library |
| 1.49% | `libc-2.31.so` | `pthread_attr_setschedparam` | libc |
| 1.38% | `python` | `gc_collect_main` | gc |
| 1.33% | `python` | `_PyObject_Malloc` | memory |
| 1.23% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.17% | `_pickle.cpython-313-x86_64-linux-gnu.so` | `memo_put.isra.0` | library |
| 1.14% | `python` | `_PyObject_Free` | memory |
| 0.71% | `_pickle.cpython-313-x86_64-linux-gnu.so` | `0x0000000000005d04` | library |
| 0.68% | `python` | `visit_decref` | gc |
| 0.55% | `python` | `_Py_dict_lookup` | lookup |
| 0.54% | `python` | `visit_reachable` | gc |
| 0.53% | `_pickle.cpython-313-x86_64-linux-gnu.so` | `0x0000000000006004` | library |
| 0.51% | `python` | `_PyThreadState_GetCurrent` | unknown |

## pickle_pure_python

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 43.01% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 3.45% | `python` | `_PyObject_Malloc` | memory |
| 3.44% | `python` | `_Py_dict_lookup` | lookup |
| 3.00% | `python` | `_PyObject_Free` | memory |
| 2.31% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.67% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 1.67% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.30% | `python` | `gc_collect_main` | gc |
| 1.06% | `python` | `_PyEval_FrameClearAndPop` | unknown |
| 1.06% | `python` | `initialize_locals` | interpreter |
| 0.94% | `python` | `tupledealloc` | memory |
| 0.77% | `python` | `PyBuffer_FillInfo` | unknown |
| 0.69% | `python` | `PyBuffer_Release` | unknown |
| 0.67% | `python` | `visit_decref` | gc |
| 0.64% | `python` | `PyDict_GetItemRef` | dict |
| 0.63% | `python` | `_PyType_Lookup` | lookup |
| 0.57% | `python` | `dict_get` | dict |
| 0.55% | `python` | `bytes_concat` | unknown |
| 0.53% | `python` | `visit_reachable` | gc |
| 0.52% | `python` | `tuple_alloc` | memory |

## pidigits

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 31.69% | `python` | `x_divrem` | int |
| 21.91% | `python` | `k_mul` | int |
| 12.08% | `python` | `x_add` | int |
| 7.69% | `python` | `x_sub` | int |
| 4.85% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 2.35% | `libc-2.31.so` | `pthread_attr_setschedparam` | libc |
| 1.62% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 0.91% | `python` | `_PyObject_Free` | memory |
| 0.87% | `python` | `_PyObject_Malloc` | memory |
| 0.87% | `python` | `gc_collect_main` | gc |
| 0.75% | `python` | `unicodekeys_lookup_unicode` | lookup |

## pprint

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 40.73% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 4.49% | `python` | `_PyObject_Malloc` | memory |
| 3.48% | `python` | `_PyObject_Free` | memory |
| 3.26% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 2.19% | `python` | `_PyType_Lookup` | lookup |
| 2.11% | `python` | `tupledealloc` | memory |
| 1.80% | `python` | `_Py_type_getattro_impl` | unknown |
| 1.72% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 1.49% | `python` | `_Py_type_getattro` | lookup |
| 1.36% | `python` | `_PyUnicode_JoinArray.part.0` | str |
| 1.15% | `python` | `_Py_dict_lookup` | lookup |
| 1.11% | `python` | `long_to_decimal_string_internal` | int |
| 1.08% | `python` | `_PyTuple_FromArraySteal` | tuple |
| 0.99% | `python` | `tuple_alloc` | memory |
| 0.98% | `python` | `set_lookkey` | set |
| 0.96% | `python` | `PyUnicode_Format` | str |
| 0.84% | `python` | `_PyEval_FrameClearAndPop` | unknown |
| 0.69% | `python` | `resize_compact` | str |
| 0.64% | `python` | `_PyTrash_end` | gc |
| 0.60% | `python` | `_copy_characters.part.0.constprop.0` | str |
| 0.59% | `python` | `initialize_locals` | interpreter |
| 0.59% | `python` | `_Py_NewReference` | memory |
| 0.54% | `python` | `subtype_dealloc` | memory |
| 0.53% | `python` | `list_dealloc` | memory |
| 0.53% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.51% | `python` | `PyUnicode_New.part.0` | memory |
| 0.50% | `python` | `_PyTrash_begin` | gc |

## pycparser

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 33.93% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 11.42% | `python` | `sre_ucs1_match` | library |
| 4.57% | `python` | `gc_collect_main` | gc |
| 2.62% | `python` | `_PyObject_Malloc` | memory |
| 2.34% | `python` | `_PyObject_Free` | memory |
| 2.21% | `libc-2.31.so` | `pthread_attr_setschedparam` | libc |
| 2.09% | `python` | `_Py_dict_lookup` | lookup |
| 1.64% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.24% | `python` | `visit_decref` | gc |
| 1.14% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.12% | `python` | `PyDict_GetItemRef` | dict |
| 1.12% | `python` | `visit_reachable` | gc |
| 1.12% | `python` | `PySlice_AdjustIndices` | slice |
| 1.10% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 0.99% | `python` | `subtype_traverse` | gc |
| 0.91% | `python` | `initialize_locals` | interpreter |
| 0.85% | `python` | `_PyType_Lookup` | lookup |
| 0.82% | `python` | `subtype_dealloc` | memory |
| 0.82% | `python` | `list_ass_slice` | list |
| 0.82% | `python` | `pattern_new_match.isra.0.part.0` | memory |
| 0.79% | `python` | `_sre_SRE_Pattern_match` | library |
| 0.76% | `python` | `sre_ucs1_count` | library |
| 0.57% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.54% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.51% | `python` | `list_dealloc` | memory |

## pyflate

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 44.63% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 3.91% | `python` | `list_ass_slice` | list |
| 3.85% | `python` | `list_dealloc` | memory |
| 3.78% | `python` | `_PyObject_Free` | memory |
| 2.96% | `python` | `_PyObject_Malloc` | memory |
| 2.95% | `python` | `list_concat` | list |
| 2.39% | `libc-2.31.so` | `pthread_attr_setschedparam` | libc |
| 2.26% | `python` | `PyNumber_AsSsize_t` | dynamic |
| 1.73% | `python` | `list_slice.isra.0` | list |
| 1.41% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 1.15% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.13% | `python` | `_PyLong_Add` | int |
| 1.05% | `python` | `_PyLong_Subtract` | int |
| 1.01% | `python` | `PyLong_AsSsize_t` | int |
| 0.91% | `python` | `PySlice_AdjustIndices` | slice |
| 0.85% | `python` | `list_sort_impl` | list |
| 0.83% | `python` | `stringlib_bytes_join` | unknown |
| 0.81% | `python` | `long_lshift` | int |
| 0.74% | `python` | `_Py_NewReference` | memory |
| 0.73% | `python` | `bytes_subscript` | unknown |
| 0.71% | `python` | `_PyBuildSlice_ConsumeRefs` | slice |
| 0.68% | `python` | `_PyEval_FrameClearAndPop` | unknown |
| 0.60% | `python` | `PyObject_GetItem` | dynamic |
| 0.60% | `python` | `unsafe_long_compare` | unknown |
| 0.58% | `python` | `long_lshift1` | int |
| 0.51% | `python` | `long_dealloc` | memory |

## python_startup

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 7.29% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 5.24% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 4.53% | `python` | `gc_collect_main` | gc |
| 3.17% | `python` | `_PyObject_Malloc` | memory |
| 2.95% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 2.60% | `python` | `visit_decref` | gc |
| 2.18% | `python` | `_Py_dict_lookup` | lookup |
| 2.18% | `python` | `visit_reachable` | gc |
| 1.94% | `python` | `r_object` | unknown |
| 1.63% | `python` | `_PyObject_Free` | memory |
| 1.60% | `python` | `update_one_slot` | unknown |
| 1.45% | `python` | `type_ready` | dynamic |
| 1.40% | `python` | `siphash13` | str |
| 1.39% | `python` | `find_name_in_mro` | lookup |
| 1.21% | `python` | `_PyCode_Quicken` | interpreter |
| 1.19% | `python` | `_Py_hashtable_get_entry_generic` | unknown |
| 1.01% | `libc-2.31.so` | `pthread_attr_setschedparam` | libc |
| 0.96% | `python` | `tupledealloc` | memory |
| 0.91% | `ld-2.31.so` | `_dl_rtld_di_serinfo` | library |
| 0.85% | `python` | `_PyType_Lookup` | lookup |
| 0.85% | `python` | `_PyUnicode_FromUCS1.part.0` | str |
| 0.84% | `[kernel.kallsyms]` | `native_irq_return_iret` | kernel |
| 0.79% | `python` | `dict_traverse` | gc |
| 0.72% | `python` | `_PyDict_GetItem_KnownHash` | dict |
| 0.72% | `python` | `ascii_decode` | str |
| 0.67% | `python` | `insertdict` | dict |
| 0.67% | `python` | `intern_string_constants` | unknown |
| 0.62% | `[kernel.kallsyms]` | `sync_regs` | kernel |
| 0.54% | `[kernel.kallsyms]` | `zap_pte_range.isra.0` | kernel |
| 0.50% | `[kernel.kallsyms]` | `clear_page_erms` | kernel |

## python_startup_no_site

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 6.72% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 5.49% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 4.74% | `python` | `gc_collect_main` | gc |
| 3.15% | `python` | `_PyObject_Malloc` | memory |
| 3.05% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 2.66% | `python` | `visit_decref` | gc |
| 2.37% | `python` | `_Py_dict_lookup` | lookup |
| 2.17% | `python` | `visit_reachable` | gc |
| 1.91% | `python` | `r_object` | unknown |
| 1.70% | `python` | `update_one_slot` | unknown |
| 1.66% | `python` | `_PyObject_Free` | memory |
| 1.60% | `python` | `type_ready` | dynamic |
| 1.52% | `python` | `find_name_in_mro` | lookup |
| 1.40% | `python` | `siphash13` | str |
| 1.25% | `python` | `_Py_hashtable_get_entry_generic` | unknown |
| 1.22% | `python` | `_PyCode_Quicken` | interpreter |
| 1.06% | `ld-2.31.so` | `_dl_rtld_di_serinfo` | library |
| 1.02% | `libc-2.31.so` | `pthread_attr_setschedparam` | libc |
| 0.91% | `python` | `tupledealloc` | memory |
| 0.89% | `[kernel.kallsyms]` | `native_irq_return_iret` | kernel |
| 0.88% | `python` | `_PyUnicode_FromUCS1.part.0` | str |
| 0.87% | `python` | `_PyType_Lookup` | lookup |
| 0.85% | `python` | `dict_traverse` | gc |
| 0.78% | `python` | `_PyDict_GetItem_KnownHash` | dict |
| 0.70% | `python` | `insertdict` | dict |
| 0.70% | `python` | `ascii_decode` | str |
| 0.70% | `python` | `intern_string_constants` | unknown |
| 0.68% | `[kernel.kallsyms]` | `sync_regs` | kernel |
| 0.64% | `[kernel.kallsyms]` | `zap_pte_range.isra.0` | kernel |
| 0.55% | `libc-2.31.so` | `__gconv_get_alias_db` | libc |
| 0.53% | `python` | `build_indices_unicode` | dict |
| 0.52% | `python` | `_PyUnicode_InternInPlace` | str |
| 0.51% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 0.51% | `libc-2.31.so` | `wcsrtombs` | libc |

## raytrace

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 52.20% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 3.53% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 2.54% | `python` | `_PyObject_Free` | memory |
| 2.04% | `python` | `_PyObject_Malloc` | memory |
| 2.03% | `python` | `_PyEval_FrameClearAndPop` | unknown |
| 1.57% | `python` | `PyFloat_FromDouble` | float |
| 1.47% | `python` | `subtype_dealloc` | memory |
| 1.43% | `python` | `float_dealloc` | memory |
| 1.28% | `python` | `PyType_IsSubtype` | dynamic |
| 1.07% | `python` | `_PyType_NewManagedObject` | memory |
| 0.96% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 0.94% | `python` | `float_sub` | float |
| 0.83% | `python` | `PyNumber_Subtract` | dynamic |
| 0.80% | `python` | `_Py_NewReference` | memory |
| 0.79% | `python` | `initialize_locals` | interpreter |
| 0.77% | `python` | `_PyThreadState_PopFrame` | interpreter |
| 0.76% | `python` | `_PyObject_FreeInstanceAttributes` | dynamic |
| 0.70% | `python` | `tupledealloc` | memory |
| 0.65% | `python` | `_PyType_Lookup` | lookup |
| 0.60% | `python` | `gc_collect_main` | gc |
| 0.59% | `python` | `PyLong_AsDouble` | int |
| 0.57% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.56% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.54% | `python` | `vectorcall_maybe.constprop.0` | unknown |

## regex_compile

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 39.97% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 3.48% | `python` | `sre_ucs1_match` | library |
| 3.45% | `python` | `_PyObject_Malloc` | memory |
| 3.07% | `python` | `_PyObject_Free` | memory |
| 1.86% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.46% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 1.27% | `python` | `PyNumber_AsSsize_t` | dynamic |
| 1.17% | `python` | `tupledealloc` | memory |
| 1.08% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.06% | `python` | `_PyType_Lookup` | lookup |
| 0.98% | `python` | `gc_collect_main` | gc |
| 0.77% | `python` | `bytearray_ass_subscript` | unknown |
| 0.73% | `python` | `sre_ucs2_charset.isra.0` | library |
| 0.68% | `python` | `PyLong_FromLong` | int |
| 0.62% | `python` | `_PyEval_FrameClearAndPop` | unknown |
| 0.61% | `python` | `list_dealloc` | memory |
| 0.58% | `python` | `initialize_locals` | interpreter |
| 0.58% | `python` | `tuple_alloc` | memory |
| 0.56% | `python` | `_Py_dict_lookup` | lookup |
| 0.54% | `python` | `sre_search` | library |
| 0.50% | `python` | `PyObject_GC_Del` | gc |

## regex_dna

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 32.94% | `python` | `sre_ucs1_match` | library |
| 26.09% | `python` | `sre_ucs2_charset.isra.0` | library |
| 7.33% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 6.44% | `python` | `sre_search` | library |
| 3.03% | `libm-2.31.so` | `__fmod_finite` | library |
| 1.45% | `_bisect.cpython-313-x86_64-linux-gnu.so` | `_bisect_bisect_right` | library |
| 1.24% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 0.97% | `python` | `pattern_subx` | library |
| 0.74% | `python` | `float_rem` | float |
| 0.71% | `python` | `gc_collect_main` | gc |
| 0.67% | `python` | `_PyObject_Malloc` | memory |
| 0.66% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.60% | `python` | `float_richcompare` | float |

## regex_effbot

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 37.66% | `python` | `sre_ucs1_match` | library |
| 13.45% | `python` | `sre_ucs2_charset.isra.0` | library |
| 6.30% | `python` | `sre_search` | library |
| 6.15% | `python` | `_PyObject_Malloc` | memory |
| 5.81% | `python` | `_PyObject_Free` | memory |
| 5.08% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 2.09% | `python` | `sre_ucs1_count` | library |
| 1.11% | `python` | `gc_collect_main` | gc |
| 0.99% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.75% | `python` | `PyObject_Malloc` | dynamic |
| 0.70% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 0.60% | `python` | `visit_decref` | gc |
| 0.52% | `python` | `_Py_dict_lookup` | lookup |

## regex_v8

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 31.47% | `python` | `sre_ucs1_match` | library |
| 9.70% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 4.27% | `python` | `sre_search` | library |
| 3.67% | `python` | `sre_ucs1_count` | library |
| 3.15% | `python` | `PyCode_Addr2Line` | unknown |
| 2.51% | `python` | `_PyObject_Malloc` | memory |
| 2.26% | `python` | `_PyObject_Free` | memory |
| 2.14% | `libc-2.31.so` | `pthread_attr_setschedparam` | libc |
| 1.62% | `python` | `pattern_subx` | library |
| 1.36% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 1.35% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.91% | `python` | `gc_collect_main` | gc |
| 0.91% | `python` | `pattern_new_match.isra.0.part.0` | memory |
| 0.90% | `python` | `_sre_SRE_Pattern_search` | library |
| 0.86% | `python` | `_Py_dict_lookup` | lookup |
| 0.71% | `python` | `visit_decref` | gc |
| 0.58% | `libc-2.31.so` | `malloc` | libc |
| 0.52% | `python` | `_PyType_Lookup` | lookup |
| 0.52% | `python` | `visit_reachable` | gc |

## richards

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 50.95% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 5.04% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 3.83% | `python` | `_PyType_Lookup` | lookup |
| 2.75% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 2.43% | `python` | `PyObject_GenericGetAttr` | dynamic |
| 1.75% | `python` | `_PyObject_GetMethod` | dynamic |
| 1.75% | `python` | `_PyObject_GetInstanceAttribute` | dynamic |
| 1.45% | `python` | `_PyEval_FrameClearAndPop` | unknown |
| 1.27% | `python` | `gc_collect_main` | gc |
| 1.24% | `python` | `PyObject_GetAttr` | dynamic |
| 1.17% | `python` | `_PyObject_Malloc` | memory |
| 1.03% | `python` | `_PyObject_Free` | memory |
| 0.95% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 0.93% | `python` | `_Py_dict_lookup` | lookup |
| 0.71% | `python` | `visit_decref` | gc |
| 0.65% | `python` | `initialize_locals` | interpreter |
| 0.55% | `python` | `_PyThreadState_PopFrame` | interpreter |

## richards_super

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 51.00% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 4.94% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 3.89% | `python` | `_PyType_Lookup` | lookup |
| 2.82% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 2.23% | `python` | `PyObject_GenericGetAttr` | dynamic |
| 1.85% | `python` | `_PyObject_GetMethod` | dynamic |
| 1.69% | `python` | `_PyObject_GetInstanceAttribute` | dynamic |
| 1.59% | `python` | `_PyEval_FrameClearAndPop` | unknown |
| 1.27% | `python` | `PyObject_GetAttr` | dynamic |
| 1.17% | `python` | `gc_collect_main` | gc |
| 1.10% | `python` | `_PyObject_Free` | memory |
| 1.07% | `python` | `_PyObject_Malloc` | memory |
| 0.88% | `python` | `_Py_dict_lookup` | lookup |
| 0.85% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 0.71% | `python` | `PyDict_GetItemRef` | dict |
| 0.60% | `python` | `_PyObject_GenericSetAttrWithDict` | dynamic |
| 0.60% | `python` | `visit_decref` | gc |
| 0.59% | `python` | `_PyObject_StoreInstanceAttribute` | dynamic |
| 0.56% | `python` | `_PyThreadState_PopFrame` | interpreter |
| 0.54% | `python` | `do_super_lookup` | unknown |
| 0.52% | `python` | `initialize_locals` | interpreter |

## scimark

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 40.03% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 5.30% | `python` | `PyNumber_AsSsize_t` | dynamic |
| 4.01% | `python` | `_PyObject_Free` | memory |
| 3.79% | `python` | `_PyObject_Malloc` | memory |
| 3.43% | `array.cpython-313-x86_64-linux-gnu.so` | `array_subscr` | library |
| 3.21% | `python` | `PyFloat_FromDouble` | float |
| 2.40% | `python` | `PyType_GetModuleByDef` | unknown |
| 2.27% | `python` | `vgetargs1_impl` | unknown |
| 2.20% | `python` | `PyObject_GetItem` | dynamic |
| 1.77% | `python` | `convertitem.constprop.0` | unknown |
| 1.66% | `python` | `PyLong_AsSsize_t` | int |
| 1.64% | `python` | `_PyLong_Add` | int |
| 1.46% | `python` | `float_dealloc` | memory |
| 1.21% | `array.cpython-313-x86_64-linux-gnu.so` | `array_ass_subscr` | library |
| 1.21% | `python` | `PyLong_FromLong` | int |
| 1.05% | `python` | `_Py_NewReference` | memory |
| 0.98% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 0.75% | `array.cpython-313-x86_64-linux-gnu.so` | `d_setitem` | library |
| 0.73% | `python` | `long_dealloc` | memory |
| 0.72% | `python` | `PyIndex_Check` | unknown |
| 0.72% | `python` | `_PyFloat_ExactDealloc` | memory |
| 0.71% | `python` | `PyArg_Parse` | unknown |
| 0.71% | `python` | `_PyLong_Multiply` | int |
| 0.69% | `python` | `PyObject_SetItem` | dynamic |
| 0.55% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |

## spectral_norm

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 34.37% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 7.48% | `python` | `_PyObject_Free` | memory |
| 6.50% | `python` | `_PyLong_Add` | int |
| 5.93% | `python` | `_PyObject_Malloc` | memory |
| 3.15% | `python` | `float_div` | float |
| 2.66% | `python` | `long_div` | int |
| 2.11% | `python` | `_PyLong_Multiply` | int |
| 1.80% | `python` | `listiter_next` | list |
| 1.75% | `python` | `enum_next` | unknown |
| 1.52% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.47% | `python` | `PyType_IsSubtype` | dynamic |
| 1.31% | `python` | `PyLong_AsDouble` | int |
| 1.24% | `python` | `PyLong_FromLong` | int |
| 1.21% | `python` | `gc_collect_main` | gc |
| 1.16% | `python` | `_Py_NewReference` | memory |
| 1.15% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.11% | `python` | `PyNumber_TrueDivide` | dynamic |
| 0.93% | `python` | `long_dealloc` | memory |
| 0.82% | `python` | `_PyEval_FrameClearAndPop` | unknown |
| 0.81% | `python` | `PyNumber_FloorDivide` | dynamic |
| 0.74% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 0.61% | `python` | `visit_decref` | gc |
| 0.58% | `python` | `PyObject_Malloc` | dynamic |
| 0.52% | `python` | `PyLong_FromSsize_t` | int |

## sqlalchemy_declarative

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 23.87% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 4.81% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 3.18% | `python` | `gc_collect_main` | gc |
| 2.76% | `python` | `_Py_dict_lookup` | lookup |
| 2.35% | `python` | `_PyObject_Malloc` | memory |
| 2.07% | `python` | `_PyType_Lookup` | lookup |
| 2.02% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 1.86% | `python` | `visit_decref` | gc |
| 1.84% | `python` | `_PyObject_Free` | memory |
| 1.57% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.50% | `python` | `visit_reachable` | gc |
| 1.36% | `python` | `tupledealloc` | memory |
| 1.32% | `python` | `PyObject_GenericGetAttr` | dynamic |
| 0.86% | `python` | `PyObject_GetAttr` | dynamic |
| 0.84% | `python` | `initialize_locals` | interpreter |
| 0.82% | `python` | `_PyDict_GetItem_KnownHash` | dict |
| 0.73% | `libpthread-2.31.so` | `__pthread_mutex_lock` | library |
| 0.68% | `libpthread-2.31.so` | `pthread_mutex_unlock` | library |
| 0.60% | `python` | `PyObject_IsTrue` | dynamic |
| 0.56% | `python` | `find_name_in_mro` | lookup |
| 0.54% | `python` | `_PyObject_GetMethod` | dynamic |
| 0.54% | `python` | `sre_ucs1_match` | library |
| 0.53% | `python` | `_PyObject_GC_New` | gc |
| 0.52% | `python` | `insertdict` | dict |
| 0.51% | `python` | `dict_traverse` | gc |

## sqlalchemy_imperative

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 28.24% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 4.85% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 2.56% | `python` | `gc_collect_main` | gc |
| 2.33% | `python` | `_Py_dict_lookup` | lookup |
| 2.31% | `python` | `_PyObject_Malloc` | memory |
| 2.26% | `python` | `_PyType_Lookup` | lookup |
| 2.15% | `python` | `PyObject_GenericGetAttr` | dynamic |
| 1.72% | `python` | `_PyObject_Free` | memory |
| 1.68% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 1.34% | `python` | `tupledealloc` | memory |
| 1.25% | `python` | `PyObject_GetAttr` | dynamic |
| 1.16% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.12% | `python` | `visit_decref` | gc |
| 0.92% | `python` | `initialize_locals` | interpreter |
| 0.77% | `python` | `visit_reachable` | gc |
| 0.64% | `libpthread-2.31.so` | `__pthread_mutex_lock` | library |
| 0.62% | `python` | `PyDict_GetItemWithError` | dict |
| 0.61% | `python` | `_PyObject_GetMethod` | dynamic |
| 0.60% | `python` | `PyObject_IsTrue` | dynamic |
| 0.58% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.57% | `python` | `subtype_dealloc` | memory |
| 0.56% | `python` | `sre_ucs1_match` | library |
| 0.54% | `python` | `_PyObject_GC_New` | gc |
| 0.54% | `python` | `tuple_alloc` | memory |
| 0.50% | `python` | `insertdict` | dict |

## sqlglot

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 39.65% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 3.09% | `python` | `_PyObject_Malloc` | memory |
| 3.02% | `python` | `_PyObject_Free` | memory |
| 2.55% | `python` | `_PyType_Lookup` | lookup |
| 2.07% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.94% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.48% | `python` | `gc_collect_main` | gc |
| 1.44% | `python` | `PyType_IsSubtype` | dynamic |
| 1.29% | `python` | `_Py_dict_lookup` | lookup |
| 1.27% | `python` | `tupledealloc` | memory |
| 1.24% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 1.18% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.93% | `python` | `dictiter_iternextitem` | unknown |
| 0.83% | `python` | `_PyEval_FrameClearAndPop` | unknown |
| 0.81% | `python` | `initialize_locals` | interpreter |
| 0.74% | `python` | `_PyObject_GC_New` | gc |
| 0.73% | `python` | `visit_decref` | gc |
| 0.69% | `python` | `PyObject_GC_Del` | gc |
| 0.56% | `python` | `PyObject_GetAttr` | dynamic |
| 0.53% | `python` | `PyObject_IsInstance` | dynamic |
| 0.53% | `python` | `tuple_alloc` | memory |

## sqlite_synth

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 10.38% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 8.95% | `libpthread-2.31.so` | `__pthread_mutex_lock` | library |
| 8.90% | `libpthread-2.31.so` | `pthread_mutex_unlock` | library |
| 3.88% | `libsqlite3.so.0.8.6` | `sqlite3_reset` | library |
| 2.95% | `python` | `_PyObject_Malloc` | memory |
| 2.86% | `python` | `_PyObject_Free` | memory |
| 2.05% | `python` | `take_gil` | unknown |
| 1.96% | `libm-2.31.so` | `f64xsubf128` | library |
| 1.39% | `python` | `gc_collect_main` | gc |
| 1.39% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.15% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 1.09% | `python` | `tupledealloc` | memory |
| 0.98% | `libsqlite3.so.0.8.6` | `sqlite3_randomness` | library |
| 0.81% | `python` | `drop_gil` | unknown |
| 0.80% | `libc-2.31.so` | `pthread_attr_setschedparam` | libc |
| 0.78% | `_sqlite3.cpython-313-x86_64-linux-gnu.so` | `_pysqlite_query_execute` | library |
| 0.77% | `libpthread-2.31.so` | `pthread_cond_signal@@GLIBC_2.3.2` | library |
| 0.76% | `libsqlite3.so.0.8.6` | `sqlite3_value_double` | library |
| 0.72% | `python` | `visit_decref` | gc |
| 0.71% | `libsqlite3.so.0.8.6` | `sqlite3_preupdate_old` | library |
| 0.62% | `python` | `_Py_dict_lookup` | lookup |
| 0.57% | `libsqlite3.so.0.8.6` | `sqlite3_value_int64` | library |
| 0.57% | `python` | `list_dealloc` | memory |
| 0.55% | `libsqlite3.so.0.8.6` | `sqlite3_extended_errcode` | library |
| 0.55% | `libsqlite3.so.0.8.6` | `sqlite3_wal_checkpoint` | library |
| 0.55% | `python` | `PyThread_get_thread_ident` | unknown |
| 0.55% | `python` | `_PyThreadState_MustExit` | unknown |
| 0.54% | `python` | `visit_reachable` | gc |
| 0.53% | `python` | `long_to_decimal_string_internal` | int |
| 0.52% | `libsqlite3.so.0.8.6` | `sqlite3_vtab_config` | library |
| 0.52% | `python` | `PyList_New` | memory |
| 0.52% | `python` | `PyFloat_FromDouble` | float |
| 0.52% | `python` | `_Py_NewReference` | memory |

## sympy

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 26.43% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 3.43% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 2.89% | `python` | `_PyObject_Malloc` | memory |
| 2.55% | `python` | `_PyType_Lookup` | lookup |
| 2.42% | `python` | `_PyObject_Free` | memory |
| 2.04% | `python` | `tupledealloc` | memory |
| 2.02% | `python` | `_Py_dict_lookup` | lookup |
| 1.96% | `python` | `gc_collect_main` | gc |
| 1.73% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 1.60% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.41% | `python` | `initialize_locals` | interpreter |
| 1.18% | `python` | `PyObject_RichCompareBool` | dynamic |
| 0.95% | `python` | `visit_decref` | gc |
| 0.91% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.91% | `python` | `PyType_IsSubtype` | dynamic |
| 0.72% | `python` | `tuple_alloc` | memory |
| 0.67% | `python` | `_Py_type_getattro` | lookup |
| 0.66% | `python` | `PyObject_GetAttr` | dynamic |
| 0.66% | `python` | `visit_reachable` | gc |
| 0.64% | `python` | `insertdict` | dict |
| 0.63% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.62% | `python` | `PyDict_GetItemRef` | dict |
| 0.59% | `python` | `_PyObject_GC_New` | gc |
| 0.58% | `python` | `PyObject_GenericGetAttr` | dynamic |
| 0.58% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.56% | `python` | `_PyTrash_end` | gc |
| 0.56% | `python` | `PyObject_GC_Del` | gc |
| 0.51% | `python` | `setiter_iternext` | set |

## telco

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 14.27% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 4.76% | `python` | `PyType_GetModuleByDef` | unknown |
| 4.69% | `python` | `_PyObject_Free` | memory |
| 4.20% | `python` | `_PyObject_Malloc` | memory |
| 1.95% | `_decimal.cpython-313-x86_64-linux-gnu.so` | `nm_mpd_qadd` | library |
| 1.91% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 1.88% | `python` | `PyContextVar_Get` | unknown |
| 1.79% | `_decimal.cpython-313-x86_64-linux-gnu.so` | `_mpd_qaddsub` | library |
| 1.73% | `python` | `tupledealloc` | memory |
| 1.71% | `python` | `_PyObject_GC_New` | gc |
| 1.66% | `python` | `PyObject_GC_Del` | gc |
| 1.48% | `_decimal.cpython-313-x86_64-linux-gnu.so` | `mpd_setdigits` | library |
| 1.44% | `_decimal.cpython-313-x86_64-linux-gnu.so` | `_mpd_qmul` | library |
| 1.35% | `_decimal.cpython-313-x86_64-linux-gnu.so` | `_mpd_check_exp` | library |
| 1.26% | `_decimal.cpython-313-x86_64-linux-gnu.so` | `nm_mpd_qmul` | library |
| 1.26% | `python` | `_PyArg_UnpackKeywordsWithVararg` | unknown |
| 1.17% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.14% | `python` | `PyObject_GenericGetAttr` | dynamic |
| 1.07% | `python` | `vgetargskeywords.constprop.0` | unknown |
| 1.05% | `_decimal.cpython-313-x86_64-linux-gnu.so` | `_mpd_baseshiftr` | library |
| 1.00% | `python` | `gc_collect_main` | gc |
| 0.99% | `python` | `_PyType_Lookup` | lookup |
| 0.92% | `python` | `convertitem.constprop.0` | unknown |
| 0.87% | `_decimal.cpython-313-x86_64-linux-gnu.so` | `PyDecType_New` | library |
| 0.84% | `_decimal.cpython-313-x86_64-linux-gnu.so` | `mpd_qquantize` | library |
| 0.83% | `_decimal.cpython-313-x86_64-linux-gnu.so` | `dec_addstatus` | library |
| 0.83% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.78% | `_decimal.cpython-313-x86_64-linux-gnu.so` | `dec_mpd_qquantize` | library |
| 0.76% | `_decimal.cpython-313-x86_64-linux-gnu.so` | `dec_dealloc` | library |
| 0.74% | `python` | `PyUnicode_AsUCS4` | str |
| 0.71% | `python` | `_Py_NewReference` | memory |
| 0.70% | `python` | `vgetargs1_impl` | unknown |
| 0.69% | `python` | `PyCMethod_New` | memory |
| 0.68% | `_decimal.cpython-313-x86_64-linux-gnu.so` | `mpd_qshiftr` | library |
| 0.66% | `python` | `meth_dealloc` | memory |
| 0.62% | `python` | `_PyTuple_FromArray` | tuple |
| 0.58% | `python` | `visit_decref` | gc |
| 0.57% | `python` | `_Py_dict_lookup` | lookup |
| 0.55% | `_decimal.cpython-313-x86_64-linux-gnu.so` | `mpd_qfinalize.part.0` | library |
| 0.53% | `python` | `_PyObject_GC_Link` | gc |
| 0.53% | `python` | `_PyTrash_end` | gc |
| 0.52% | `_decimal.cpython-313-x86_64-linux-gnu.so` | `_mpd_baseadd` | library |
| 0.50% | `python` | `tuple_alloc` | memory |

## thrift

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 21.65% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 3.61% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 3.32% | `python` | `_PyObject_Malloc` | memory |
| 2.94% | `python` | `initialize_locals` | interpreter |
| 2.77% | `python` | `_PyObject_Free` | memory |
| 1.89% | `python` | `PyObject_GenericGetAttr` | dynamic |
| 1.83% | `python` | `_PyType_Lookup` | lookup |
| 1.71% | `fastbinary.cpython-312-x86_64-linux-gnu.so` | `apache::thrift::py::ProtocolBase<apache::thrift::py::BinaryProtocol>::encodeValue` | library |
| 1.62% | `python` | `insert_to_emptydict` | dict |
| 1.56% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 1.46% | `python` | `_Py_dict_lookup` | lookup |
| 1.41% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.32% | `python` | `insertdict` | dict |
| 1.15% | `python` | `subtype_dealloc` | memory |
| 1.13% | `python` | `gc_collect_main` | gc |
| 1.12% | `python` | `tupledealloc` | memory |
| 0.98% | `python` | `PyType_GenericAlloc` | memory |
| 0.89% | `python` | `dict_dealloc` | memory |
| 0.88% | `python` | `_PyObject_Call_Prepend` | dynamic |
| 0.86% | `python` | `_PyStack_UnpackDict` | unknown |
| 0.81% | `python` | `PyObject_GetAttr` | dynamic |
| 0.80% | `python` | `slot_tp_init` | unknown |
| 0.80% | `python` | `PyUnicode_FromFormatV` | str |
| 0.75% | `python` | `_PyTrash_begin` | gc |
| 0.74% | `python` | `_PyObject_MakeTpCall` | dynamic |
| 0.70% | `python` | `free_keys_object` | dict |
| 0.67% | `python` | `PyObject_RichCompare` | dynamic |
| 0.67% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.66% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.65% | `python` | `_Py_NewReference` | memory |
| 0.64% | `python` | `_PyTrash_end` | gc |
| 0.62% | `python` | `PyLong_AsLong` | int |
| 0.61% | `fastbinary.cpython-312-x86_64-linux-gnu.so` | `apache::thrift::py::ProtocolBase<apache::thrift::py::BinaryProtocol>::decodeValue` | library |
| 0.58% | `python` | `list_dealloc` | memory |
| 0.57% | `python` | `PyTuple_Size` | tuple |
| 0.56% | `python` | `_PyObject_InitializeDict` | dynamic |
| 0.54% | `python` | `PyDict_GetItemWithError` | dict |
| 0.54% | `python` | `PyDict_SetItem` | dict |
| 0.51% | `python` | `_Py_Dealloc` | memory |

## tomli_loads

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 46.84% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 4.15% | `python` | `set_lookkey` | set |
| 3.73% | `python` | `_PyObject_Free` | memory |
| 3.19% | `python` | `_PyObject_Malloc` | memory |
| 2.67% | `python` | `_PyLong_Add` | int |
| 2.62% | `python` | `_PyUnicode_Equal` | str |
| 2.53% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 2.21% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 2.07% | `python` | `PySequence_Contains` | dynamic |
| 1.62% | `python` | `set_contains` | set |
| 1.39% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.35% | `python` | `_Py_dict_lookup` | lookup |
| 1.23% | `python` | `PyDict_GetItemRef` | dict |
| 0.92% | `python` | `tupledealloc` | memory |
| 0.77% | `python` | `_PyIncrementalNewlineDecoder_decode` | memory |
| 0.76% | `python` | `long_dealloc` | memory |
| 0.73% | `python` | `replace` | str |
| 0.63% | `python` | `_Py_NewReference` | memory |
| 0.61% | `python` | `_PyUnicode_FromUCS4.part.0` | str |
| 0.60% | `python` | `PyNumber_AsSsize_t` | dynamic |
| 0.54% | `python` | `_PyTuple_FromArraySteal` | tuple |
| 0.54% | `python` | `tuple_alloc` | memory |
| 0.50% | `python` | `sre_ucs4_match` | library |

## tornado_http

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 26.62% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 3.60% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 2.72% | `python` | `_PyObject_Malloc` | memory |
| 2.55% | `python` | `gc_collect_main` | gc |
| 2.37% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.98% | `python` | `_PyObject_Free` | memory |
| 1.57% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.33% | `python` | `visit_decref` | gc |
| 1.24% | `python` | `_PyType_Lookup` | lookup |
| 1.18% | `python` | `_Py_dict_lookup` | lookup |
| 1.17% | `python` | `tupledealloc` | memory |
| 1.08% | `python` | `visit_reachable` | gc |
| 0.88% | `python` | `initialize_locals` | interpreter |
| 0.80% | `libc-2.31.so` | `pthread_attr_setschedparam` | libc |
| 0.68% | `[kernel.kallsyms]` | `copy_user_enhanced_fast_string` | kernel |
| 0.58% | `python` | `r_object` | unknown |
| 0.52% | `python` | `PyObject_GC_UnTrack` | gc |

## typing_runtime_protocols

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 29.75% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 2.99% | `python` | `_PyObject_Malloc` | memory |
| 2.96% | `python` | `_Py_dict_lookup` | lookup |
| 2.79% | `python` | `_PyObject_Free` | memory |
| 2.45% | `python` | `tupledealloc` | memory |
| 2.29% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 2.11% | `python` | `_PyType_Lookup` | lookup |
| 1.81% | `python` | `_PyObject_MakeTpCall` | dynamic |
| 1.55% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.52% | `python` | `_Py_type_getattro` | lookup |
| 1.52% | `python` | `_PyTuple_FromArray` | tuple |
| 1.51% | `python` | `PyObject_RichCompareBool` | dynamic |
| 1.38% | `python` | `tuple_alloc` | memory |
| 1.21% | `python` | `gc_collect_main` | gc |
| 1.12% | `python` | `tuplehash` | tuple |
| 1.08% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 1.07% | `python` | `bounded_lru_cache_wrapper` | unknown |
| 0.91% | `python` | `_PyObject_GC_New` | gc |
| 0.83% | `python` | `PyObject_Vectorcall` | dynamic |
| 0.82% | `python` | `_PyTrash_end` | gc |
| 0.80% | `python` | `_PyEval_FrameClearAndPop` | unknown |
| 0.74% | `python` | `PyObject_GenericGetAttr` | dynamic |
| 0.72% | `python` | `PyObject_GC_Del` | gc |
| 0.71% | `python` | `frame_dealloc` | memory |
| 0.70% | `python` | `set_lookkey` | set |
| 0.64% | `python` | `_PyDict_GetItem_KnownHash` | dict |
| 0.63% | `python` | `PyObject_Hash` | dynamic |
| 0.63% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.60% | `python` | `getset_get` | unknown |
| 0.60% | `python` | `_PyTrash_begin` | gc |
| 0.59% | `python` | `_Py_NewReference` | memory |
| 0.58% | `python` | `visit_decref` | gc |
| 0.56% | `python` | `wrap_descr_get` | unknown |
| 0.53% | `python` | `PyObject_GetAttr` | dynamic |
| 0.50% | `python` | `PyDict_GetItemRef` | dict |

## unpack_sequence

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 75.96% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 1.13% | `python` | `gc_collect_main` | gc |
| 1.04% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.91% | `python` | `_PyObject_Malloc` | memory |
| 0.69% | `python` | `_PyObject_Free` | memory |
| 0.64% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 0.61% | `python` | `visit_decref` | gc |

## unpickle

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 7.65% | `_pickle.cpython-313-x86_64-linux-gnu.so` | `load` | library |
| 7.54% | `python` | `_PyObject_Malloc` | memory |
| 5.90% | `python` | `_PyObject_Free` | memory |
| 5.51% | `python` | `siphash13` | str |
| 4.69% | `python` | `insertdict` | dict |
| 4.57% | `_pickle.cpython-313-x86_64-linux-gnu.so` | `load_counted_binunicode` | library |
| 4.45% | `python` | `ascii_decode` | str |
| 4.15% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 3.87% | `python` | `unicode_decode_utf8` | str |
| 3.63% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 2.75% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 2.48% | `python` | `PyUnicode_New.part.0` | memory |
| 2.40% | `_pickle.cpython-313-x86_64-linux-gnu.so` | `do_setitems.isra.0` | library |
| 2.20% | `python` | `_Py_dict_lookup` | lookup |
| 1.75% | `_pickle.cpython-313-x86_64-linux-gnu.so` | `_Unpickler_MemoPut` | library |
| 1.73% | `python` | `dict_ass_sub` | dict |
| 1.33% | `python` | `free_keys_object` | dict |
| 1.14% | `python` | `find_empty_slot` | dict |
| 1.12% | `_pickle.cpython-313-x86_64-linux-gnu.so` | `Unpickler_clear` | library |
| 1.10% | `python` | `_PyObject_Realloc` | memory |
| 1.10% | `python` | `PyObject_SetItem` | dynamic |
| 1.02% | `python` | `unicode_dealloc` | memory |
| 0.98% | `python` | `build_indices_unicode` | dict |
| 0.89% | `python` | `gc_collect_main` | gc |
| 0.75% | `python` | `PyObject_IS_GC` | gc |
| 0.69% | `python` | `_Py_NewReference` | memory |
| 0.67% | `_pickle.cpython-313-x86_64-linux-gnu.so` | `Pdata_push` | library |
| 0.61% | `libc-2.31.so` | `pthread_attr_setschedparam` | libc |
| 0.58% | `python` | `list_dealloc` | memory |

## unpickle_list

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 15.18% | `_pickle.cpython-313-x86_64-linux-gnu.so` | `load` | library |
| 6.72% | `python` | `list_dealloc` | memory |
| 5.88% | `python` | `PyList_New` | memory |
| 5.82% | `python` | `_PyObject_Free` | memory |
| 5.59% | `python` | `list_ass_slice` | list |
| 4.95% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 4.58% | `python` | `_PyObject_Malloc` | memory |
| 4.21% | `_pickle.cpython-313-x86_64-linux-gnu.so` | `do_append.isra.0` | library |
| 4.04% | `_pickle.cpython-313-x86_64-linux-gnu.so` | `Pdata_push` | library |
| 3.39% | `python` | `PyLong_FromLong` | int |
| 2.22% | `python` | `_PyObject_Calloc` | memory |
| 1.96% | `python` | `PyMem_Calloc` | memory |
| 1.67% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 1.64% | `python` | `_Py_NewReference` | memory |
| 1.25% | `python` | `gc_collect_main` | gc |
| 1.16% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.15% | `python` | `_PyObject_Realloc` | memory |
| 1.07% | `python` | `_PyTrash_end` | gc |
| 1.04% | `python` | `_Py_Dealloc` | memory |
| 1.04% | `_pickle.cpython-313-x86_64-linux-gnu.so` | `marker.isra.0` | library |
| 1.02% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.94% | `python` | `_PyTrash_begin` | gc |
| 0.71% | `_pickle.cpython-313-x86_64-linux-gnu.so` | `_Unpickler_MemoPut` | library |
| 0.61% | `_pickle.cpython-313-x86_64-linux-gnu.so` | `0x0000000000005be4` | library |

## unpickle_pure_python

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 47.35% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 2.30% | `python` | `_Py_dict_lookup` | lookup |
| 2.26% | `python` | `_PyObject_Malloc` | memory |
| 1.91% | `python` | `PyObject_IsTrue` | dynamic |
| 1.89% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.68% | `python` | `_PyObject_Free` | memory |
| 1.60% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 1.39% | `python` | `PyNumber_AsSsize_t` | dynamic |
| 1.34% | `python` | `PyDict_GetItemRef` | dict |
| 1.16% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.09% | `python` | `_PyEval_FrameClearAndPop` | unknown |
| 1.06% | `python` | `insertdict` | dict |
| 0.99% | `python` | `initialize_locals` | interpreter |
| 0.93% | `python` | `_io_BytesIO_read` | unknown |
| 0.88% | `python` | `gc_collect_main` | gc |
| 0.84% | `python` | `bytes_subscript` | unknown |
| 0.83% | `python` | `unicode_decode_utf8` | str |
| 0.81% | `python` | `list_subscript` | list |
| 0.80% | `python` | `tupledealloc` | memory |
| 0.73% | `python` | `PyObject_GetItem` | dynamic |
| 0.68% | `python` | `PyLong_AsSsize_t` | int |
| 0.64% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.62% | `python` | `PyUnicode_Decode.part.0` | str |
| 0.59% | `python` | `ascii_decode` | str |
| 0.56% | `python` | `_Py_convert_optional_to_ssize_t` | unknown |
| 0.54% | `python` | `PyBytes_FromStringAndSize` | unknown |
| 0.53% | `python` | `siphash13` | str |
| 0.50% | `python` | `PyObject_IsInstance` | dynamic |

## xml_etree

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 19.13% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 4.02% | `python` | `_PyObject_Malloc` | memory |
| 2.95% | `python` | `_PyObject_Free` | memory |
| 2.85% | `python` | `gc_collect_main` | gc |
| 2.36% | `pyexpat.cpython-313-x86_64-linux-gnu.so` | `normal_updatePosition` | library |
| 2.01% | `pyexpat.cpython-313-x86_64-linux-gnu.so` | `normal_contentTok` | library |
| 2.00% | `python` | `_PyType_Lookup` | lookup |
| 1.91% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 1.74% | `python` | `visit_decref` | gc |
| 1.66% | `python` | `PyObject_GenericGetAttr` | dynamic |
| 1.64% | `python` | `visit_reachable` | gc |
| 1.51% | `python` | `_io_TextIOWrapper_write` | unknown |
| 1.45% | `python` | `_Py_dict_lookup` | lookup |
| 1.41% | `pyexpat.cpython-313-x86_64-linux-gnu.so` | `sip24_update` | library |
| 1.17% | `pyexpat.cpython-313-x86_64-linux-gnu.so` | `accountingDiffTolerated.part.0` | library |
| 1.13% | `pyexpat.cpython-313-x86_64-linux-gnu.so` | `normal_nameLength` | library |
| 1.01% | `_elementtree.cpython-313-x86_64-linux-gnu.so` | `expat_end_handler` | library |
| 0.99% | `pyexpat.cpython-313-x86_64-linux-gnu.so` | `doContent` | library |
| 0.96% | `python` | `initialize_locals` | interpreter |
| 0.94% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.93% | `pyexpat.cpython-313-x86_64-linux-gnu.so` | `lookup.constprop.0` | library |
| 0.88% | `python` | `tupledealloc` | memory |
| 0.87% | `_elementtree.cpython-313-x86_64-linux-gnu.so` | `treebuilder_handle_start` | library |
| 0.84% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 0.77% | `_elementtree.cpython-313-x86_64-linux-gnu.so` | `element_gc_traverse` | library |
| 0.76% | `python` | `PyUnicode_Contains` | str |
| 0.68% | `_elementtree.cpython-313-x86_64-linux-gnu.so` | `elementiter_next` | library |
| 0.68% | `python` | `siphash13` | str |
| 0.63% | `python` | `PyObject_GetAttr` | dynamic |
| 0.62% | `pyexpat.cpython-313-x86_64-linux-gnu.so` | `normal_getAtts` | library |
| 0.61% | `python` | `_copy_characters.part.0.constprop.0` | str |
| 0.60% | `python` | `_PyObject_GetMethod` | dynamic |
| 0.59% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.59% | `python` | `ascii_decode` | str |
| 0.59% | `python` | `PyUnicode_New.part.0` | memory |
| 0.58% | `python` | `list_dealloc` | memory |
| 0.58% | `pyexpat.cpython-313-x86_64-linux-gnu.so` | `sip24_final` | library |
| 0.57% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.57% | `python` | `getset_get` | unknown |
| 0.55% | `python` | `PyObject_GC_UnTrack` | gc |


## Categories

### interpreter

29.86% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 27.15% | python | _PyEval_EvalFrameDefault |
| 1.20% | python | _PyFrame_ClearExceptCode |
| 0.62% | python | initialize_locals |
| 0.30% | python | _PyEvalFramePushAndInit |
| 0.21% | python | _PyCode_Quicken |
| 0.19% | python | _PyThreadState_PopFrame |
| 0.15% | python | _PyEval_Vector |
| 0.04% | python | advance |
| 0.01% | python | _PyFrame_New_NoTrack |

### memory

11.38% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 2.84% | python | _PyObject_Malloc |
| 2.49% | python | _PyObject_Free |
| 0.74% | python | tupledealloc |
| 0.49% | python | list_dealloc |
| 0.46% | python | _Py_NewReference |
| 0.29% | python | tuple_alloc |
| 0.25% | python | subtype_dealloc |
| 0.25% | python | _Py_Dealloc |
| 0.22% | python | PyUnicode_New.part.0 |
| 0.21% | python | PyType_GenericAlloc |
| 0.19% | python | _PyObject_Realloc |
| 0.16% | python | dict_dealloc |
| 0.14% | python | PyList_New |
| 0.14% | python | gen_dealloc |
| 0.14% | python | unicode_dealloc |
| 0.13% | python | _PyLong_New |
| 0.12% | python | code_dealloc |
| 0.12% | python | float_dealloc |
| 0.12% | python | long_dealloc |
| 0.10% | python | _PyObject_Calloc |
| 0.09% | python | set_dealloc |
| 0.09% | python | PyFunction_NewWithQualName |
| 0.09% | python | PyTuple_New |
| 0.07% | python | PyCMethod_New |
| 0.07% | python | meth_dealloc |
| 0.07% | python | slice_dealloc |
| 0.07% | python | func_dealloc |
| 0.06% | python | PyMem_Calloc |
| 0.06% | python | _PyCode_New |
| 0.06% | python | frame_dealloc |
| 0.05% | python | allocate_from_new_pool |
| 0.05% | python | pattern_new_match.isra.0.part.0 |
| 0.05% | python | PyObject_CallFinalizerFromDealloc |
| 0.05% | python | PyUnicode_New |
| 0.05% | python | PyDict_New |
| 0.04% | python | object_new |
| 0.04% | python | method_dealloc |
| 0.04% | python | _PyType_NewManagedObject |
| 0.04% | python | PyMethod_New |
| 0.03% | python | _PyObject_Malloc (inlined) |
| 0.03% | python | PySlice_New |
| 0.03% | python | listiter_dealloc |
| 0.03% | python | context_tp_dealloc |
| 0.03% | python | PyMem_Free |
| 0.02% | python | _PyFloat_ExactDealloc |
| 0.02% | python | type_new |
| 0.02% | python | StopIteration_dealloc |
| 0.02% | python | object_dealloc |
| 0.02% | python | tb_dealloc |
| 0.02% | python | BaseException_new |
| 0.02% | python | async_gen_wrapped_val_dealloc |
| 0.02% | python | PyMem_Malloc |
| 0.02% | python | _PyObject_New |
| 0.02% | python | _PyAsyncGenValueWrapperNew |
| 0.02% | python | async_gen_asend_dealloc |
| 0.02% | python | PyMem_Realloc |
| 0.02% | python | tp_new_wrapper |
| 0.01% | python | _PyIncrementalNewlineDecoder_decode |
| 0.01% | python | tupleiter_dealloc |
| 0.01% | python | cell_dealloc |
| 0.01% | python | weakref___new__ |
| 0.01% | python | structseq_dealloc |
| 0.01% | python | PyWeakref_NewRef |
| 0.01% | python | range_dealloc |
| 0.01% | python | PyCell_New |
| 0.01% | python | BaseException_dealloc |
| 0.01% | python | unicode_new |
| 0.01% | python | reversed_new_impl |
| 0.01% | python | dictiter_dealloc |
| 0.01% | python | match_dealloc |
| 0.01% | python | PyList_New.constprop.0 |
| 0.01% | python | type_dealloc |

### gc

11.17% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 4.27% | python | gc_collect_main |
| 1.71% | python | visit_decref |
| 1.71% | python | visit_reachable |
| 0.36% | python | PyObject_GC_UnTrack |
| 0.33% | python | PyObject_GC_Del |
| 0.29% | python | subtype_traverse |
| 0.27% | python | list_traverse |
| 0.27% | python | _PyTrash_end |
| 0.26% | python | _PyObject_GC_New |
| 0.25% | python | dict_traverse |
| 0.21% | python | _PyTrash_begin |
| 0.20% | python | PyObject_IS_GC |
| 0.17% | python | _PyObject_GC_Link |
| 0.14% | python | _PyObject_GC_NewVar |
| 0.13% | python | set_traverse |
| 0.10% | python | func_traverse |
| 0.08% | python | _PyTrash_cond |
| 0.07% | python | type_is_gc |
| 0.06% | python | _PyDict_MaybeUntrack |
| 0.05% | python | type_traverse |
| 0.05% | python | _PyTuple_MaybeUntrack |
| 0.05% | python | gen_traverse |
| 0.03% | python | PyObject_GC_Track |
| 0.03% | python | meth_traverse |
| 0.02% | python | context_tp_traverse |
| 0.02% | python | gc_traverse |
| 0.01% | python | descr_traverse |
| 0.01% | python | module_traverse |
| 0.01% | python | _PyObject_VisitManagedDict |
| 0.01% | python | method_traverse |

### library

9.64% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 1.60% | python | sre_ucs1_match |
| 1.23% | _pickle.cpython-313-x86_64-linux-gnu.so | save |
| 0.77% | libz.so.1.2.11 | crc32_combine64 |
| 0.62% | python | sre_ucs2_charset.isra.0 |
| 0.32% | _json.cpython-313-x86_64-linux-gnu.so | scanstring_unicode |
| 0.31% | _pickle.cpython-313-x86_64-linux-gnu.so | _Pickler_Write |
| 0.28% | libz.so.1.2.11 | inflateBackEnd |
| 0.28% | _pickle.cpython-313-x86_64-linux-gnu.so | load |
| 0.23% | python | sre_search |
| 0.18% | libpthread-2.31.so | __pthread_mutex_lock |
| 0.17% | _json.cpython-313-x86_64-linux-gnu.so | scan_once_unicode |
| 0.17% | libpthread-2.31.so | pthread_mutex_unlock |
| 0.17% | _pickle.cpython-313-x86_64-linux-gnu.so | PyMemoTable_Set |
| 0.15% | _pickle.cpython-313-x86_64-linux-gnu.so | _Pickler_Write.constprop.3 |
| 0.14% | python | sre_ucs1_count |
| 0.13% | libm-2.31.so | f64xsubf128 |
| 0.10% | ld-2.31.so | _dl_rtld_di_serinfo |
| 0.08% | _pickle.cpython-313-x86_64-linux-gnu.so | Pickler_clear |
| 0.08% | _json.cpython-313-x86_64-linux-gnu.so | py_encode_basestring_ascii |
| 0.07% | tracer.cpython-313-x86_64-linux-gnu.so | CTracer_trace |
| 0.07% | libpython3.11.so.1.0 | _PyEval_EvalFrameDefault |
| 0.06% | _pickle.cpython-313-x86_64-linux-gnu.so | memo_put.isra.0 |
| 0.06% | libsqlite3.so.0.8.6 | sqlite3_reset |
| 0.06% | _pickle.cpython-313-x86_64-linux-gnu.so | Pdata_push |
| 0.06% | _pickle.cpython-313-x86_64-linux-gnu.so | load_counted_binunicode |
| 0.05% | _pickle.cpython-313-x86_64-linux-gnu.so | do_append.isra.0 |
| 0.05% | _asyncio.cpython-313-x86_64-linux-gnu.so | TaskObj_traverse |
| 0.05% | libmagic.so.1.0.0 | 0x000000000000f936 |
| 0.05% | python | _sre_SRE_Pattern_match |
| 0.04% | python | pattern_subx |
| 0.04% | array.cpython-313-x86_64-linux-gnu.so | array_subscr |
| 0.04% | libz.so.1.2.11 | inflateCodesUsed |
| 0.04% | libm-2.31.so | __fmod_finite |
| 0.03% | libmagic.so.1.0.0 | 0x000000000000f932 |
| 0.03% | ld-2.31.so | _dl_catch_error |
| 0.03% | _json.cpython-313-x86_64-linux-gnu.so | encoder_listencode_obj |
| 0.03% | _pickle.cpython-313-x86_64-linux-gnu.so | _Unpickler_MemoPut |
| 0.03% | _pickle.cpython-313-x86_64-linux-gnu.so | do_setitems.isra.0 |
| 0.03% | pyexpat.cpython-313-x86_64-linux-gnu.so | normal_updatePosition |
| 0.03% | python | _sre_SRE_Pattern_search |
| 0.02% | pyexpat.cpython-313-x86_64-linux-gnu.so | normal_contentTok |
| 0.02% | _decimal.cpython-313-x86_64-linux-gnu.so | nm_mpd_qadd |
| 0.02% | math.cpython-313-x86_64-linux-gnu.so | factorial_partial_product |
| 0.02% | _decimal.cpython-313-x86_64-linux-gnu.so | _mpd_qaddsub |
| 0.02% | _pickle.cpython-313-x86_64-linux-gnu.so | memo_get.isra.0 |
| 0.02% | libpthread-2.31.so | pthread_cond_signal@@GLIBC_2.3.2 |
| 0.02% | fastbinary.cpython-312-x86_64-linux-gnu.so | apache::thrift::py::ProtocolBase<apache::thrift::py::BinaryProtocol>::encodeValue |
| 0.02% | _json.cpython-313-x86_64-linux-gnu.so | encoder_encode_key_value |
| 0.02% | _pickle.cpython-313-x86_64-linux-gnu.so | Unpickler_clear |
| 0.02% | _decimal.cpython-313-x86_64-linux-gnu.so | mpd_setdigits |
| 0.02% | libz.so.1.2.11 | inflate |
| 0.02% | _bisect.cpython-313-x86_64-linux-gnu.so | _bisect_bisect_right |
| 0.02% | libpthread-2.31.so | __errno_location |
| 0.02% | _decimal.cpython-313-x86_64-linux-gnu.so | _mpd_qmul |
| 0.02% | _pickle.cpython-313-x86_64-linux-gnu.so | 0x0000000000005d04 |
| 0.02% | _asyncio.cpython-313-x86_64-linux-gnu.so | task_step_impl |
| 0.02% | libsqlite3.so.0.8.6 | sqlite3_randomness |
| 0.02% | pyexpat.cpython-313-x86_64-linux-gnu.so | sip24_update |
| 0.02% | _decimal.cpython-313-x86_64-linux-gnu.so | _mpd_check_exp |
| 0.02% | array.cpython-313-x86_64-linux-gnu.so | array_ass_subscr |
| 0.02% | _decimal.cpython-313-x86_64-linux-gnu.so | nm_mpd_qmul |
| 0.01% | _asyncio.cpython-313-x86_64-linux-gnu.so | TaskObj_clear |
| 0.01% | libpython3.11.so.1.0 | _PyDict_GetItem_KnownHash |
| 0.01% | libsqlite3.so.0.8.6 | sqlite3_exec |
| 0.01% | pyexpat.cpython-313-x86_64-linux-gnu.so | accountingDiffTolerated.part.0 |
| 0.01% | _pickle.cpython-313-x86_64-linux-gnu.so | marker.isra.0 |
| 0.01% | pyexpat.cpython-313-x86_64-linux-gnu.so | normal_nameLength |
| 0.01% | _decimal.cpython-313-x86_64-linux-gnu.so | _mpd_baseshiftr |
| 0.01% | _heapq.cpython-313-x86_64-linux-gnu.so | siftup |
| 0.01% | _asyncio.cpython-313-x86_64-linux-gnu.so | TaskStepMethWrapper_traverse |
| 0.01% | _elementtree.cpython-313-x86_64-linux-gnu.so | expat_end_handler |
| 0.01% | pyexpat.cpython-313-x86_64-linux-gnu.so | doContent |
| 0.01% | libpthread-2.31.so | sem_trywait@@GLIBC_2.2.5 |
| 0.01% | libpython3.11.so.1.0 | PyObject_Malloc |
| 0.01% | _elementtree.cpython-313-x86_64-linux-gnu.so | element_gc_traverse |
| 0.01% | _pickle.cpython-313-x86_64-linux-gnu.so | 0x0000000000005e94 |
| 0.01% | pyexpat.cpython-313-x86_64-linux-gnu.so | lookup.constprop.0 |
| 0.01% | libsqlite3.so.0.8.6 | sqlite3_value_double |
| 0.01% | libpthread-2.31.so | sem_post@@GLIBC_2.2.5 |
| 0.01% | _asyncio.cpython-313-x86_64-linux-gnu.so | future_init |
| 0.01% | libpython3.11.so.1.0 | deduce_unreachable |
| 0.01% | _pickle.cpython-313-x86_64-linux-gnu.so | 0x0000000000006004 |
| 0.01% | _decimal.cpython-313-x86_64-linux-gnu.so | PyDecType_New |
| 0.01% | _elementtree.cpython-313-x86_64-linux-gnu.so | treebuilder_handle_start |
| 0.01% | libssl.so.1.1 | SSL_rstate_string |
| 0.01% | _asyncio.cpython-313-x86_64-linux-gnu.so | FutureObj_traverse |
| 0.01% | libpython3.11.so.1.0 | visit_decref |
| 0.01% | _decimal.cpython-313-x86_64-linux-gnu.so | mpd_qquantize |
| 0.01% | _decimal.cpython-313-x86_64-linux-gnu.so | dec_addstatus |
| 0.01% | _asyncio.cpython-313-x86_64-linux-gnu.so | _asyncio_Task___init__ |
| 0.01% | _sqlite3.cpython-313-x86_64-linux-gnu.so | _pysqlite_query_execute |
| 0.01% | _decimal.cpython-313-x86_64-linux-gnu.so | dec_mpd_qquantize |
| 0.01% | libsqlite3.so.0.8.6 | sqlite3_preupdate_old |
| 0.01% | _decimal.cpython-313-x86_64-linux-gnu.so | dec_dealloc |
| 0.01% | array.cpython-313-x86_64-linux-gnu.so | d_setitem |
| 0.01% | _asyncio.cpython-313-x86_64-linux-gnu.so | task_step |
| 0.01% | libsqlite3.so.0.8.6 | sqlite3_value_int64 |
| 0.01% | libpython3.11.so.1.0 | type_new |
| 0.01% | libpython3.11.so.1.0 | PyDict_SetDefault |
| 0.01% | _decimal.cpython-313-x86_64-linux-gnu.so | mpd_qshiftr |
| 0.01% | _elementtree.cpython-313-x86_64-linux-gnu.so | elementiter_next |
| 0.01% | libsqlite3.so.0.8.6 | sqlite3_wal_checkpoint |
| 0.01% | _asyncio.cpython-313-x86_64-linux-gnu.so | _asyncio_Future_add_done_callback |
| 0.01% | math.cpython-313-x86_64-linux-gnu.so | math_sqrt |
| 0.01% | _asyncio.cpython-313-x86_64-linux-gnu.so | future_schedule_callbacks |
| 0.01% | _pickle.cpython-313-x86_64-linux-gnu.so | 0x0000000000005be4 |
| 0.01% | libsqlite3.so.0.8.6 | sqlite3_vtab_config |
| 0.01% | libsqlite3.so.0.8.6 | sqlite3_extended_errcode |
| 0.01% | pyexpat.cpython-313-x86_64-linux-gnu.so | normal_getAtts |
| 0.01% | fastbinary.cpython-312-x86_64-linux-gnu.so | apache::thrift::py::ProtocolBase<apache::thrift::py::BinaryProtocol>::decodeValue |
| 0.01% | libpython3.11.so.1.0 | visit_reachable |
| 0.01% | libsqlite3.so.0.8.6 | sqlite3_str_value |
| 0.01% | pyexpat.cpython-313-x86_64-linux-gnu.so | sip24_final |
| 0.01% | _decimal.cpython-313-x86_64-linux-gnu.so | mpd_qfinalize.part.0 |
| 0.01% | libpython3.11.so.1.0 | gc_collect_main |
| 0.01% | _random.cpython-313-x86_64-linux-gnu.so | genrand_uint32 |
| 0.01% | _pickle.cpython-313-x86_64-linux-gnu.so | _Unpickler_New |
| 0.01% | libsqlite3.so.0.8.6 | sqlite3_step |
| 0.01% | _decimal.cpython-313-x86_64-linux-gnu.so | _mpd_baseadd |
| 0.01% | _pickle.cpython-313-x86_64-linux-gnu.so | _Pickler_New.isra.0 |
| 0.01% | python | sre_ucs4_match |

### unknown

7.61% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 0.46% | python | _PyEval_FrameClearAndPop |
| 0.31% | python | r_object |
| 0.26% | python | update_one_slot |
| 0.16% | python | _Py_hashtable_get_entry_generic |
| 0.14% | python | PyType_GetModuleByDef |
| 0.13% | python | _PyErr_SetObject.part.0 |
| 0.12% | python | intern_string_constants |
| 0.11% | python | vgetargs1_impl |
| 0.11% | python | _PyType_GetDict |
| 0.09% | python | convertitem.constprop.0 |
| 0.09% | python | _PyThreadState_PushFrame |
| 0.09% | python | _PyPegen_is_memoized |
| 0.08% | python | _PyFunction_Vectorcall |
| 0.08% | python | PyErr_CheckSignals |
| 0.08% | python | call_instrumentation_vector.part.0 |
| 0.07% | python | _Py_CheckFunctionResult |
| 0.07% | python | make_gen |
| 0.07% | python | new_keys_object |
| 0.07% | python | vgetargskeywords.constprop.0 |
| 0.07% | python | PyCode_Addr2Line |
| 0.07% | python | slot_tp_init |
| 0.07% | python | PyErr_Occurred |
| 0.07% | python | _PyFrame_Traverse |
| 0.07% | python | gen_iternext |
| 0.07% | python | getset_get |
| 0.06% | python | _Py_GetBaseOpcode |
| 0.06% | python | _PyIO_find_line_ending |
| 0.06% | python | memset@plt |
| 0.05% | python | compute_range_length |
| 0.05% | python | PyBytes_FromStringAndSize |
| 0.05% | python | func_clear |
| 0.05% | python | take_gil |
| 0.05% | python | memcpy@plt |
| 0.05% | python | PyThreadState_GetUnchecked |
| 0.05% | python | object_isinstance |
| 0.05% | python | PyThread_get_thread_ident |
| 0.04% | python | PyIter_Next |
| 0.04% | python | method_vectorcall |
| 0.04% | python | dictiter_iternextitem |
| 0.04% | python | _PyPegen_expect_token |
| 0.04% | python | dictresize |
| 0.04% | python | do_super_lookup |
| 0.04% | python | PyDescr_IsData |
| 0.04% | python | _PyStack_UnpackDict |
| 0.04% | python | _Py_type_getattro_impl |
| 0.04% | python | range_iter |
| 0.04% | python | _Py_call_instrumentation_line |
| 0.03% | python | async_gen_asend_iternext |
| 0.03% | python | _PyArg_UnpackKeywords |
| 0.03% | python | PyBool_FromLong |
| 0.03% | python | _PyCfg_OptimizeCodeUnit |
| 0.03% | python | method_get |
| 0.03% | python | deque_append |
| 0.03% | python | _Py_HashBytes |
| 0.03% | python | enum_next |
| 0.03% | python | min_max |
| 0.03% | python | _PyPegen_update_memo |
| 0.03% | python | PyErr_ExceptionMatches |
| 0.03% | python | context_run |
| 0.03% | python | split |
| 0.03% | python | PyArg_UnpackTuple |
| 0.03% | [vdso] | __vdso_clock_gettime |
| 0.03% | python | PyTraceBack_Here |
| 0.03% | python | PyBuffer_Release |
| 0.03% | python | method_vectorcall_VARARGS |
| 0.03% | python | StopIteration_init |
| 0.03% | python | _PyErr_Restore |
| 0.03% | python | tok_get_normal_mode |
| 0.03% | python | sys_audit_tstate |
| 0.03% | python | do_mkvalue |
| 0.03% | python | delitem_common |
| 0.02% | python | PyIter_Send |
| 0.02% | python | PyContextVar_Get |
| 0.02% | python | bytes_subscript |
| 0.02% | python | slot_tp_richcompare |
| 0.02% | python | dequeiter_next |
| 0.02% | python | bounded_lru_cache_wrapper |
| 0.02% | python | cfunction_vectorcall_FASTCALL_KEYWORDS |
| 0.02% | python | clone_combined_dict_keys.isra.0 |
| 0.02% | python | _Py_MakeCoro |
| 0.02% | python | tailmatch |
| 0.02% | python | tok_nextc |
| 0.02% | python | pysiphash |
| 0.02% | python | code_hash |
| 0.02% | python | method_vectorcall_FASTCALL_KEYWORDS_METHOD |
| 0.02% | python | cfunction_vectorcall_NOARGS |
| 0.02% | python | drop_gil |
| 0.02% | python | bytearray_ass_subscript |
| 0.02% | python | PyImport_ImportModuleLevelObject |
| 0.02% | python | _PyFrame_Copy |
| 0.02% | python | hashtable_unicode_compare |
| 0.02% | python | _PySuper_Lookup |
| 0.02% | python | _io_TextIOWrapper_write |
| 0.02% | python | _PyGen_Finalize |
| 0.02% | python | _PyGen_FetchStopIterationValue |
| 0.02% | python | r_string (inlined) |
| 0.02% | python | cfunction_call |
| 0.02% | python | PySys_Audit |
| 0.02% | python | async_gen_anext |
| 0.02% | python | primary_rule |
| 0.02% | python | stringlib_bytes_join |
| 0.02% | python | _PyCode_Validate |
| 0.02% | python | builtin_getattr |
| 0.02% | python | term_rule |
| 0.02% | python | _PyArena_Malloc |
| 0.02% | python | object_richcompare |
| 0.02% | python | _PyErr_ExceptionMatches (inlined) |
| 0.02% | python | _PyPegen_fill_token |
| 0.02% | python | _PyAssemble_MakeCodeObject |
| 0.02% | python | _PyEval_BuiltinsFromGlobals |
| 0.02% | python | _PyArg_UnpackKeywordsWithVararg |
| 0.02% | python | hashtable_unicode_hash |
| 0.01% | python | _PyCoro_GetAwaitableIter |
| 0.01% | python | memcmp@plt |
| 0.01% | python | PyArg_ParseTupleAndKeywords |
| 0.01% | python | PyBuffer_FillInfo |
| 0.01% | python | PyArg_ParseTuple |
| 0.01% | python | _io_BytesIO_read |
| 0.01% | python | BaseException_init |
| 0.01% | python | range_subscript |
| 0.01% | python | builtin_sum |
| 0.01% | python | cfunction_vectorcall_O |
| 0.01% | python | range_vectorcall |
| 0.01% | python | _Py_hashtable_get |
| 0.01% | python | BaseException_clear |
| 0.01% | python | slot_tp_iternext |
| 0.01% | python | map_next |
| 0.01% | python | PyMember_GetOne |
| 0.01% | python | pthread_self@plt |
| 0.01% | python | build_indices_generic |
| 0.01% | python | deque_popleft |
| 0.01% | python | PyErr_GetRaisedException |
| 0.01% | python | _PyModule_ClearDict |
| 0.01% | python | countformat |
| 0.01% | python | slot_tp_hash |
| 0.01% | python | dictiter_iternextkey |
| 0.01% | python | _PyErr_CreateException |
| 0.01% | python | _PyGen_SetStopIterationValue |
| 0.01% | python | method_vectorcall_NOARGS |
| 0.01% | python | PyIndex_Check |
| 0.01% | python | build_string |
| 0.01% | python | _PyThreadState_GetCurrent |
| 0.01% | python | dictiter_iternextvalue |
| 0.01% | python | _io_open |
| 0.01% | python | _Py_bytes_lower |
| 0.01% | python | _PyPegen_insert_memo |
| 0.01% | python | r_byte |
| 0.01% | python | any_find_slice |
| 0.01% | python | _PyThreadState_MustExit |
| 0.01% | python | _Py_Specialize_Call |
| 0.01% | python | unsafe_tuple_compare |
| 0.01% | python | object_get_class |
| 0.01% | python | _PyThreadState_Attach |
| 0.01% | python | builtin_hasattr |
| 0.01% | python | PySet_Add |
| 0.01% | python | object_vacall |
| 0.01% | python | r_string |
| 0.01% | python | vectorcall_maybe.constprop.0 |
| 0.01% | python | PyBytes_Repr |
| 0.01% | python | convertitem |
| 0.01% | python | vectorcall_method |
| 0.01% | python | tok_get |
| 0.01% | python | _Py_convert_optional_to_ssize_t |
| 0.01% | python | _Py_Specialize_LoadAttr |
| 0.01% | python | method_vectorcall_VARARGS_KEYWORDS |
| 0.01% | python | PyArg_Parse |
| 0.01% | python | inversion_rule |
| 0.01% | python | compiler_visit_expr1 |
| 0.01% | python | _Py_HashPointer |
| 0.01% | python | make_dict_from_instance_attributes |
| 0.01% | python | _PyThreadState_UncheckedGet |
| 0.01% | python | lru_cache_make_key |
| 0.01% | python | _PyFrame_MakeAndSetFrameObject |
| 0.01% | python | analyze_descriptor |
| 0.01% | python | mro_implementation |
| 0.01% | python | _PyThreadState_Detach |
| 0.01% | python | slot_mp_ass_subscript |
| 0.01% | python | stringio_iternext |
| 0.01% | python | subtype_clear |
| 0.01% | python | object_recursive_isinstance |
| 0.01% | python | PyErr_SetRaisedException |
| 0.01% | python | object_init |
| 0.01% | python | shift_expr_rule |
| 0.01% | python | PyContext_CopyCurrent |
| 0.01% | python | sum_rule |
| 0.01% | python | vgetargskeywords |
| 0.01% | python | method_vectorcall_FASTCALL |
| 0.01% | python | mro_internal |
| 0.01% | python | fill_time |
| 0.01% | python | super_getattro |
| 0.01% | python | unsafe_latin_compare |
| 0.01% | python | va_build_value |
| 0.01% | python | deque_clear.part.0 |
| 0.01% | python | PyMember_SetOne |
| 0.01% | python | slot_mp_subscript |
| 0.01% | python | PyGen_am_send |
| 0.01% | python | _PyType_FromMetaclass_impl |
| 0.01% | python | _PyErr_SetKeyError |
| 0.01% | python | _PyPegen_name_token |
| 0.01% | python | _PyCode_GetCode |
| 0.01% | python | PyEval_SaveThread |
| 0.01% | python | PyException_GetTraceback |
| 0.01% | python | strlen@plt |
| 0.01% | python | slot_sq_contains |
| 0.01% | python | symtable_visit_expr |
| 0.01% | python | _PyBytes_Resize |
| 0.01% | python | bytes_concat |
| 0.01% | python | unsafe_long_compare |
| 0.01% | python | update_slot |
| 0.01% | python | wrap_descr_get |
| 0.01% | python | _Py_call_instrumentation_jump |
| 0.01% | python | bytes_richcompare |
| 0.01% | python | sys_trace_start |
| 0.01% | python | sys_trace_return |
| 0.01% | python | member_get |
| 0.01% | python | _PyFunction_SetVersion |
| 0.01% | python | assemble |
| 0.01% | python | binary_op1 |
| 0.01% | python | builtin_id |
| 0.01% | python | func_descr_get |
| 0.01% | python | weakref_hash |
| 0.01% | python | _PyObjectDict_SetItem |
| 0.01% | python | AttributeError_init |
| 0.01% | python | _PyCfg_OptimizedCfgToInstructionSequence |
| 0.01% | python | _abc__abc_instancecheck |
| 0.01% | python | builtin___build_class__ |
| 0.01% | python | findchar |
| 0.01% | python | method_vectorcall_O |
| 0.01% | python | astfold_expr |
| 0.01% | python | PyErr_GivenExceptionMatches |
| 0.01% | python | cfunction_vectorcall_FASTCALL_KEYWORDS_METHOD |
| 0.01% | python | slot_tp_iter |
| 0.01% | python | _io_FileIO___init__ |
| 0.01% | python | weakref_richcompare |
| 0.01% | python | dictitems_iter |
| 0.01% | python | builtin_any |
| 0.01% | python | _Py_slot_tp_getattr_hook |

### dynamic

5.04% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 0.37% | python | PyObject_GenericGetAttr |
| 0.29% | python | PyObject_RichCompareBool |
| 0.29% | python | PyObject_Hash |
| 0.28% | python | PyType_IsSubtype |
| 0.27% | python | _PyObject_GetMethod |
| 0.23% | python | PyObject_GetAttr |
| 0.21% | python | PyNumber_AsSsize_t |
| 0.19% | python | _PyObject_GenericGetAttrWithDict |
| 0.18% | python | _PyObject_MakeTpCall |
| 0.16% | python | PyObject_Malloc |
| 0.15% | python | PyObject_Vectorcall |
| 0.14% | python | type_ready |
| 0.14% | python | PyObject_IsTrue |
| 0.13% | python | PyObject_VisitManagedDict |
| 0.12% | python | _PyObject_GetInstanceAttribute |
| 0.11% | python | PyObject_Free |
| 0.11% | python | PyObject_GetItem |
| 0.10% | python | PySequence_Contains |
| 0.09% | python | type_call |
| 0.08% | python | PyObject_GetIter |
| 0.07% | python | PyObject_RichCompare |
| 0.07% | python | _PyObject_GenericSetAttrWithDict |
| 0.07% | python | PyObject_GetOptionalAttr |
| 0.07% | python | _PyObject_FreeInstanceAttributes |
| 0.07% | python | _PyObject_Call_Prepend |
| 0.06% | python | PyObject_CallOneArg |
| 0.06% | python | PyObject_Call |
| 0.06% | python | PyObject_SetAttr |
| 0.05% | python | PyObject_SetItem |
| 0.05% | python | PyObject_IsInstance |
| 0.04% | python | PyObject_ClearWeakRefs |
| 0.04% | python | _PyObject_LookupSpecial |
| 0.04% | python | PyObject_Size |
| 0.04% | python | PyNumber_Add |
| 0.04% | python | PyNumber_Multiply |
| 0.03% | python | PyObject_VectorcallMethod |
| 0.03% | python | PyNumber_And |
| 0.03% | python | _PyObject_InitializeDict |
| 0.03% | python | PyObject_Str |
| 0.03% | python | _PyObject_StoreInstanceAttribute |
| 0.03% | python | PySequence_Fast |
| 0.03% | python | PyNumber_TrueDivide |
| 0.02% | python | PyObject_GenericSetAttr |
| 0.02% | python | PyNumber_Subtract |
| 0.02% | python | PySequence_Tuple |
| 0.02% | python | PyNumber_Remainder |
| 0.02% | python | _PyObject_InitInlineValues |
| 0.02% | python | PyNumber_Index |
| 0.01% | python | PyNumber_FloorDivide |
| 0.01% | python | _PyObject_LookupAttr |
| 0.01% | python | _PyObject_CallFunctionVa |
| 0.01% | python | _PyNumber_Index |
| 0.01% | python | PyNumber_Xor |
| 0.01% | python | PyNumber_Rshift |
| 0.01% | python | PyNumber_InPlaceAdd |
| 0.01% | python | PyObject_IsSubclass |
| 0.01% | python | PyObject_DelItem |
| 0.01% | python | PyObject_ClearManagedDict |
| 0.01% | python | type_mro_modified |
| 0.01% | python | PyObject_GetBuffer |
| 0.01% | python | PyObject_SelfIter |
| 0.01% | python | PyMapping_Check |
| 0.01% | python | PyObject_LengthHint |
| 0.01% | python | PyMapping_GetOptionalItem |
| 0.01% | python | PyNumber_InPlaceTrueDivide |
| 0.01% | python | _PyNumber_PowerNoMod |
| 0.01% | python | PyNumber_Long |

### lookup

4.46% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 1.90% | python | unicodekeys_lookup_unicode |
| 1.27% | python | _Py_dict_lookup |
| 0.89% | python | _PyType_Lookup |
| 0.25% | python | find_name_in_mro |
| 0.14% | python | _Py_type_getattro |

### kernel

4.13% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 0.63% | [kernel.kallsyms] | copy_user_enhanced_fast_string |
| 0.25% | [kernel.kallsyms] | clear_page_erms |
| 0.16% | [kernel.kallsyms] | native_irq_return_iret |
| 0.11% | [kernel.kallsyms] | sync_regs |
| 0.09% | [kernel.kallsyms] | zap_pte_range.isra.0 |
| 0.09% | [kernel.kallsyms] | __d_lookup_rcu |
| 0.08% | [kernel.kallsyms] | rmqueue |
| 0.07% | [kernel.kallsyms] | _raw_spin_lock |
| 0.06% | [kernel.kallsyms] | __handle_mm_fault |
| 0.06% | [kernel.kallsyms] | smp_call_function_single |
| 0.05% | [kernel.kallsyms] | free_pcppages_bulk |
| 0.04% | [kernel.kallsyms] | release_pages |
| 0.04% | [kernel.kallsyms] | copy_pte_range.isra.0 |
| 0.04% | [kernel.kallsyms] | memset_erms |
| 0.04% | [kernel.kallsyms] | try_charge |
| 0.04% | [kernel.kallsyms] | page_remove_rmap |
| 0.04% | [kernel.kallsyms] | link_path_walk.part.0 |
| 0.03% | [kernel.kallsyms] | kmem_cache_alloc |
| 0.03% | [kernel.kallsyms] | get_mem_cgroup_from_mm |
| 0.03% | [kernel.kallsyms] | handle_mm_fault |
| 0.03% | [kernel.kallsyms] | syscall_return_via_sysret |
| 0.03% | [kernel.kallsyms] | copy_page |
| 0.03% | [kernel.kallsyms] | __pagevec_lru_add_fn |
| 0.03% | [kernel.kallsyms] | filemap_map_pages |
| 0.03% | [kernel.kallsyms] | mem_cgroup_throttle_swaprate |
| 0.03% | [kernel.kallsyms] | __ext4fs_dirhash |
| 0.03% | [kernel.kallsyms] | ext4_htree_store_dirent |
| 0.03% | [kernel.kallsyms] | mem_cgroup_try_charge |
| 0.03% | [kernel.kallsyms] | entry_SYSCALL_64 |
| 0.02% | [kernel.kallsyms] | __alloc_pages_nodemask |
| 0.02% | [kernel.kallsyms] | do_wp_page |
| 0.02% | [kernel.kallsyms] | strncpy_from_user |
| 0.02% | [kernel.kallsyms] | kmem_cache_free |
| 0.02% | [kernel.kallsyms] | do_user_addr_fault |
| 0.02% | [kernel.kallsyms] | memcg_kmem_get_cache |
| 0.02% | [kernel.kallsyms] | find_get_entry |
| 0.02% | [kernel.kallsyms] | find_vma |
| 0.02% | [kernel.kallsyms] | page_fault |
| 0.02% | [kernel.kallsyms] | inode_permission |
| 0.02% | [kernel.kallsyms] | do_syscall_64 |
| 0.02% | [kernel.kallsyms] | filldir64 |
| 0.02% | [kernel.kallsyms] | lookup_fast |
| 0.02% | [kernel.kallsyms] | error_entry |
| 0.02% | [kernel.kallsyms] | vmacache_find |
| 0.02% | [kernel.kallsyms] | __virt_addr_valid |
| 0.02% | [kernel.kallsyms] | memcpy_erms |
| 0.02% | [kernel.kallsyms] | __count_memcg_events |
| 0.02% | [kernel.kallsyms] | __slab_free |
| 0.02% | [kernel.kallsyms] | get_page_from_freelist |
| 0.02% | [kernel.kallsyms] | do_anonymous_page |
| 0.02% | [kernel.kallsyms] | prep_new_page |
| 0.01% | [kernel.kallsyms] | kfree |
| 0.01% | [kernel.kallsyms] | generic_permission |
| 0.01% | [kernel.kallsyms] | walk_component |
| 0.01% | [kernel.kallsyms] | perf_iterate_ctx |
| 0.01% | [kernel.kallsyms] | str2hashbuf_signed |
| 0.01% | [kernel.kallsyms] | _raw_spin_lock_irqsave |
| 0.01% | [kernel.kallsyms] | rb_insert_color |
| 0.01% | [kernel.kallsyms] | __mod_memcg_state |
| 0.01% | [kernel.kallsyms] | ext4_getattr |
| 0.01% | [kernel.kallsyms] | __fget_light |
| 0.01% | [kernel.kallsyms] | up_read |
| 0.01% | [kernel.kallsyms] | down_read_trylock |
| 0.01% | [kernel.kallsyms] | __mod_lruvec_state |
| 0.01% | [kernel.kallsyms] | tcp_sendmsg_locked |
| 0.01% | [kernel.kallsyms] | rb_next |
| 0.01% | [kernel.kallsyms] | _cond_resched |
| 0.01% | [kernel.kallsyms] | security_inode_getattr |
| 0.01% | [kernel.kallsyms] | free_pages_and_swap_cache |
| 0.01% | [kernel.kallsyms] | entry_SYSCALL_64_after_hwframe |
| 0.01% | [kernel.kallsyms] | psi_task_change |
| 0.01% | [kernel.kallsyms] | swapgs_restore_regs_and_return_to_usermode |
| 0.01% | [kernel.kallsyms] | vm_normal_page |
| 0.01% | [kernel.kallsyms] | xas_load |
| 0.01% | [kernel.kallsyms] | generic_file_buffered_read |
| 0.01% | [kernel.kallsyms] | __lru_cache_add |
| 0.01% | [kernel.kallsyms] | set_root |
| 0.01% | [kernel.kallsyms] | fsnotify |
| 0.01% | [kernel.kallsyms] | __vma_adjust |
| 0.01% | [kernel.kallsyms] | lru_cache_add_active_or_unevictable |
| 0.01% | [kernel.kallsyms] | alloc_pages_vma |
| 0.01% | [kernel.kallsyms] | __follow_mount_rcu.isra.0 |
| 0.01% | [kernel.kallsyms] | rcu_all_qs |
| 0.01% | [kernel.kallsyms] | __kmalloc |
| 0.01% | [kernel.kallsyms] | mem_cgroup_from_task |
| 0.01% | [kernel.kallsyms] | __check_object_size |
| 0.01% | [kernel.kallsyms] | unlock_page |
| 0.01% | [kernel.kallsyms] | pagevec_lru_move_fn |
| 0.01% | [kernel.kallsyms] | native_flush_tlb_one_user |
| 0.01% | [kernel.kallsyms] | fpregs_assert_state_consistent |
| 0.01% | [kernel.kallsyms] | update_cfs_group |
| 0.01% | [kernel.kallsyms] | vma_interval_tree_insert |
| 0.01% | [kernel.kallsyms] | __mod_node_page_state |
| 0.01% | [kernel.kallsyms] | __mod_zone_page_state |
| 0.01% | [kernel.kallsyms] | ___slab_alloc |
| 0.01% | [kernel.kallsyms] | __tcp_transmit_skb |
| 0.01% | [kernel.kallsyms] | __lock_text_start |
| 0.01% | [kernel.kallsyms] | in_group_p |
| 0.01% | [kernel.kallsyms] | security_inode_permission |
| 0.01% | [kernel.kallsyms] | free_unref_page_list |
| 0.01% | [kernel.kallsyms] | free_unref_page_prepare.part.0 |
| 0.01% | [kernel.kallsyms] | __ext4_check_dir_entry |
| 0.01% | [kernel.kallsyms] | native_write_msr |

### libc

3.36% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 2.17% | libc-2.31.so | __nss_database_lookup |
| 0.50% | libc-2.31.so | pthread_attr_setschedparam |
| 0.32% | libcrypto.so.1.1 | CRYPTO_secure_actual_size |
| 0.12% | libc-2.31.so | malloc |
| 0.04% | libc-2.31.so | free |
| 0.03% | libc-2.31.so | pthread_self |
| 0.02% | libc-2.31.so | __gconv_get_alias_db |
| 0.02% | libc-2.31.so | wcsrtombs |
| 0.02% | libc-2.31.so | clock_gettime |
| 0.01% | libc-2.31.so | __libc_realloc |
| 0.01% | libc-2.31.so | _dl_addr |

### int

3.29% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 0.66% | python | k_mul |
| 0.38% | python | x_divrem |
| 0.29% | python | _PyLong_Add |
| 0.22% | python | PyLong_FromLong |
| 0.19% | python | long_hash |
| 0.15% | python | x_add |
| 0.11% | python | PyLong_AsSsize_t |
| 0.11% | python | _PyLong_Subtract |
| 0.10% | python | long_to_decimal_string_internal |
| 0.09% | python | x_sub |
| 0.09% | python | long_richcompare |
| 0.08% | python | PyLong_AsLongAndOverflow |
| 0.08% | python | long_bitwise |
| 0.08% | python | PyLong_FromString |
| 0.07% | python | PyLong_FromSsize_t |
| 0.05% | python | PyLong_AsLongAndOverflow (inlined) |
| 0.05% | python | _PyLong_Multiply |
| 0.04% | python | long_div |
| 0.04% | python | PyLong_AsDouble |
| 0.04% | python | long_rshift1 |
| 0.04% | python | long_and |
| 0.04% | python | l_mod |
| 0.03% | python | PyLong_AsLong |
| 0.02% | python | long_mul |
| 0.02% | python | long_rshift |
| 0.02% | python | long_add |
| 0.02% | python | PyLong_FromVoidPtr |
| 0.02% | python | long_lshift1 |
| 0.02% | python | long_xor |
| 0.01% | python | long_lshift |
| 0.01% | python | PyLong_FromUnsignedLong |
| 0.01% | python | _PyLong_GCD |
| 0.01% | python | long_to_decimal_string |
| 0.01% | python | long_float |
| 0.01% | python | PyLong_FromLongLong |
| 0.01% | python | _PyLong_Frexp |
| 0.01% | python | long_mod |
| 0.01% | python | PyLong_AsInt |
| 0.01% | python | long_neg |

### str

2.42% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 0.48% | python | siphash13 |
| 0.15% | python | ascii_decode |
| 0.14% | python | _PyUnicode_FromUCS1.part.0 |
| 0.14% | python | _PyUnicode_JoinArray.part.0 |
| 0.13% | python | unicode_decode_utf8 |
| 0.10% | python | _copy_characters.part.0.constprop.0 |
| 0.09% | python | replace |
| 0.09% | python | PyUnicode_Substring |
| 0.09% | python | _PyUnicode_InternInPlace |
| 0.07% | python | resize_compact |
| 0.06% | python | _PyUnicode_FromUCS4.part.0 |
| 0.06% | python | _PyUnicode_Equal |
| 0.05% | python | PyUnicode_RichCompare |
| 0.05% | python | PyUnicode_Contains |
| 0.05% | python | PyUnicode_Format |
| 0.05% | python | _PyUnicodeWriter_WriteStr |
| 0.05% | python | PyUnicode_FromFormatV |
| 0.04% | python | PyUnicode_AsUTF8AndSize |
| 0.04% | python | PyUnicode_InternInPlace |
| 0.03% | python | _PyUnicodeWriter_PrepareInternal |
| 0.03% | python | PyUnicode_AsUCS4 |
| 0.02% | python | unicode_replace |
| 0.02% | python | unicode_hash (inlined) |
| 0.02% | python | unicode_hash |
| 0.02% | python | PyUnicode_Concat |
| 0.02% | python | unicode_startswith |
| 0.01% | python | unicode_subscript |
| 0.01% | python | _PyUnicodeWriter_WriteSubstring.part.0 |
| 0.01% | python | unicode_rstrip |
| 0.01% | python | unicode_lower |
| 0.01% | python | _PyUnicodeWriter_WriteASCIIString |
| 0.01% | python | PyUnicode_FromWideChar |
| 0.01% | python | PyUnicode_Decode.part.0 |
| 0.01% | python | unicode_join |
| 0.01% | python | PyUnicode_FromKindAndData |
| 0.01% | python | _PyUnicodeWriter_Finish |
| 0.01% | python | _PyUnicodeWriter_Init |
| 0.01% | python | unicode_encode_utf8 |
| 0.01% | python | PyUnicode_AsEncodedString.part.0 |
| 0.01% | python | _PyUnicode_TranslateCharmap |
| 0.01% | python | unicode_endswith |
| 0.01% | python | PyUnicode_InternFromString |
| 0.01% | python | unicode_repr |
| 0.01% | python | _PyUnicode_ToLowercase |
| 0.01% | python | PyUnicode_FromEncodedObject |
| 0.01% | python | _PyUnicode_IsAlpha |
| 0.01% | python | PyUnicode_Splitlines |
| 0.01% | python | unicode_rpartition |

### dict

2.40% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 0.41% | python | insertdict |
| 0.32% | python | PyDict_GetItemRef |
| 0.23% | python | PyDict_Next |
| 0.21% | python | free_keys_object |
| 0.18% | python | _PyDict_GetItem_KnownHash |
| 0.13% | python | PyDict_SetDefault |
| 0.13% | python | find_empty_slot |
| 0.10% | python | build_indices_unicode |
| 0.09% | python | dict_get |
| 0.09% | python | insert_to_emptydict |
| 0.08% | python | _PyDict_FromItems |
| 0.07% | python | PyDict_SetItem |
| 0.07% | python | PyDict_GetItemWithError |
| 0.03% | python | dict_ass_sub |
| 0.03% | python | dict_merge |
| 0.03% | python | PyDict_Contains |
| 0.03% | python | dict_subscript |
| 0.02% | python | _PyDict_SetItem_Take2 |
| 0.02% | python | _PyDict_LoadGlobal |
| 0.02% | python | PyDict_GetItem |
| 0.02% | python | _PyDict_Next.part.0 |
| 0.02% | python | _PyDict_DelItem_KnownHash |

### tuple

1.01% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 0.38% | python | tuplehash |
| 0.18% | python | _PyTuple_FromArray |
| 0.14% | python | _PyTuple_FromArraySteal |
| 0.11% | python | tupletraverse |
| 0.04% | python | tuplerichcompare |
| 0.03% | python | PyTuple_Pack |
| 0.02% | python | _PyTuple_ClearFreeList |
| 0.02% | python | tuple_iter |
| 0.02% | python | tupleiter_next |
| 0.02% | python | PyTuple_Size |
| 0.01% | python | PyTuple_GetSlice |
| 0.01% | python | tuplesubscript |
| 0.01% | python | tuplecontains |

### list

0.99% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 0.21% | python | list_ass_slice |
| 0.11% | python | list_subscript |
| 0.07% | python | list_extend |
| 0.07% | python | list_slice.isra.0 |
| 0.06% | python | _PyList_FromArraySteal |
| 0.06% | python | PyList_Append |
| 0.06% | python | listiter_next |
| 0.05% | python | list_iter |
| 0.05% | python | list_sort_impl |
| 0.04% | python | list_concat |
| 0.04% | python | list_contains |
| 0.03% | python | list_append |
| 0.03% | python | list_ass_subscript |
| 0.02% | python | _PyList_AppendTakeRefListResize |
| 0.02% | python | list_pop |
| 0.01% | python | list_insert |
| 0.01% | python | list_length |
| 0.01% | python | PyList_Size |
| 0.01% | python | list_item |

### set

0.72% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 0.24% | python | set_lookkey |
| 0.10% | python | set_add_entry |
| 0.09% | python | setiter_iternext |
| 0.09% | python | set_issubset |
| 0.04% | python | set_difference |
| 0.04% | python | set_contains |
| 0.03% | python | set_table_resize |
| 0.03% | python | set_update_internal |
| 0.01% | python | set_intersection |

### slice

0.43% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 0.19% | python | PySlice_AdjustIndices |
| 0.11% | python | _PyBuildSlice_ConsumeRefs |
| 0.07% | python | _PyEval_SliceIndex |
| 0.05% | python | PySlice_Unpack |
| 0.01% | python | _PySlice_GetLongIndices |

### float

0.39% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 0.18% | python | PyFloat_FromDouble |
| 0.08% | python | float_div |
| 0.03% | python | float_richcompare |
| 0.02% | python | float_sub |
| 0.02% | python | float_pow |
| 0.02% | python | float_mul |
| 0.01% | python | float_rem |
| 0.01% | python | PyFloat_AsDouble.part.0 |
| 0.01% | python | PyFloat_AsDouble |
| 0.01% | python | float_add |
