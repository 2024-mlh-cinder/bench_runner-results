
## 2to3

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 28.75% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 3.49% | `python` | `gc_collect_main` | gc |
| 2.85% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 2.62% | `python` | `_PyObject_Malloc` | memory |
| 2.03% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 1.91% | `python` | `_PyObject_Free` | memory |
| 1.70% | `python` | `_Py_dict_lookup` | lookup |
| 1.55% | `python` | `tupledealloc` | memory |
| 1.51% | `python` | `_PyType_Lookup` | lookup |
| 1.41% | `python` | `visit_decref` | gc |
| 1.40% | `python` | `sre_ucs1_match` | library |
| 1.15% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.04% | `python` | `visit_reachable` | gc |
| 0.93% | `python` | `PyObject_GenericGetAttr` | dynamic |
| 0.75% | `python` | `_PyPegen_is_memoized` | interpreter |
| 0.65% | `libc-2.31.so` | `pthread_attr_setschedparam` | libc |
| 0.64% | `python` | `r_object` | import |
| 0.63% | `python` | `initialize_locals` | interpreter |
| 0.58% | `python` | `tuple_alloc` | memory |
| 0.56% | `python` | `PyObject_RichCompareBool` | dynamic |
| 0.56% | `python` | `_PyTuple_FromArraySteal` | tuple |
| 0.54% | `python` | `PyObject_GetAttr` | dynamic |
| 0.54% | `python` | `siphash13` | str |
| 0.52% | `python` | `update_one_slot` | lookup |
| 0.52% | `python` | `PyObject_GC_UnTrack` | gc |

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
| 0.51% | `python` | `_PyFunction_Vectorcall` | calls |

## async_generators

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 23.28% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 8.77% | `python` | `_PyErr_SetObject.part.0` | exceptions |
| 3.53% | `python` | `_PyObject_Free` | memory |
| 3.12% | `python` | `_PyObject_Malloc` | memory |
| 2.75% | `python` | `async_gen_asend_iternext` | unknown |
| 2.43% | `python` | `PyType_GenericAlloc` | memory |
| 2.17% | `python` | `gc_collect_main` | gc |
| 2.05% | `python` | `tupledealloc` | memory |
| 1.95% | `python` | `StopIteration_init` | dynamic |
| 1.73% | `python` | `PyErr_ExceptionMatches` | exceptions |
| 1.57% | `python` | `async_gen_wrapped_val_dealloc` | memory |
| 1.51% | `python` | `StopIteration_dealloc` | memory |
| 1.44% | `python` | `_PyTuple_FromArray` | tuple |
| 1.44% | `python` | `_Py_NewReference` | memory |
| 1.39% | `python` | `_PyObject_MakeTpCall` | dynamic |
| 1.36% | `python` | `_PyGen_FetchStopIterationValue` | unknown |
| 1.33% | `python` | `async_gen_asend_dealloc` | memory |
| 1.31% | `python` | `async_gen_anext` | unknown |
| 1.29% | `python` | `_PyAsyncGenValueWrapperNew` | memory |
| 1.29% | `python` | `_PyErr_ExceptionMatches` | exceptions |
| 1.20% | `python` | `tuple_alloc` | memory |
| 1.10% | `python` | `PyObject_CallOneArg` | dynamic |
| 1.07% | `python` | `type_call` | dynamic |
| 1.06% | `python` | `_PyErr_Restore` | exceptions |
| 1.04% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.95% | `python` | `PyObject_GC_Del` | gc |
| 0.84% | `python` | `_PyGen_SetStopIterationValue` | unknown |
| 0.82% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 0.80% | `python` | `visit_reachable` | gc |
| 0.80% | `python` | `PyType_IsSubtype` | dynamic |
| 0.77% | `python` | `visit_decref` | gc |
| 0.68% | `python` | `_Py_Dealloc` | memory |
| 0.65% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 0.60% | `python` | `BaseException_new` | memory |
| 0.59% | `python` | `_PyTrash_end` | gc |
| 0.57% | `python` | `_PyErr_CreateException` | exceptions |
| 0.54% | `python` | `initialize_locals` | interpreter |
| 0.54% | `python` | `_PyObject_GC_Link` | gc |
| 0.53% | `python` | `PyObject_CallFinalizerFromDealloc` | memory |
| 0.50% | `python` | `PyObject_RichCompareBool` | dynamic |

## async_tree

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 22.86% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 19.26% | `python` | `gc_collect_main` | gc |
| 5.92% | `python` | `visit_reachable` | gc |
| 5.69% | `python` | `visit_decref` | gc |
| 2.65% | `python` | `_PyObject_Malloc` | memory |
| 1.70% | `python` | `_PyObject_Free` | memory |
| 1.30% | `python` | `initialize_locals` | interpreter |
| 1.16% | `python` | `subtype_traverse` | gc |
| 1.16% | `python` | `_PyType_Lookup` | lookup |
| 1.12% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.10% | `python` | `_Py_dict_lookup` | lookup |
| 1.05% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.00% | `python` | `_PyObject_GetMethod` | dynamic |
| 0.79% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 0.79% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.71% | `python` | `tupledealloc` | memory |
| 0.63% | `_asyncio.cpython-313-x86_64-linux-gnu.so` | `TaskObj_traverse` | library |
| 0.55% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.53% | `python` | `subtype_dealloc` | memory |
| 0.53% | `python` | `context_tp_dealloc` | memory |
| 0.50% | `python` | `_PyEval_FrameClearAndPop` | interpreter |

## async_tree_cpu_io_mixed

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 17.14% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 15.58% | `python` | `k_mul` | int |
| 14.81% | `python` | `gc_collect_main` | gc |
| 4.53% | `python` | `visit_decref` | gc |
| 4.47% | `python` | `visit_reachable` | gc |
| 3.42% | `python` | `_PyObject_Malloc` | memory |
| 2.64% | `python` | `_PyObject_Free` | memory |
| 1.61% | `python` | `PyErr_CheckSignals` | exceptions |
| 1.06% | `python` | `subtype_traverse` | gc |
| 0.95% | `math.cpython-313-x86_64-linux-gnu.so` | `factorial_partial_product` | library |
| 0.87% | `python` | `initialize_locals` | interpreter |
| 0.83% | `python` | `_PyType_Lookup` | lookup |
| 0.82% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 0.80% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 0.74% | `python` | `_PyLong_New` | memory |
| 0.73% | `python` | `_Py_dict_lookup` | lookup |
| 0.67% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.66% | `python` | `_PyObject_GetMethod` | dynamic |
| 0.61% | `python` | `PyThread_get_thread_ident` | unknown |
| 0.59% | `python` | `PyObject_GC_UnTrack` | gc |

## async_tree_cpu_io_mixed_tg

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 17.96% | `python` | `gc_collect_main` | gc |
| 15.61% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 15.35% | `python` | `k_mul` | int |
| 5.00% | `python` | `visit_reachable` | gc |
| 4.75% | `python` | `visit_decref` | gc |
| 3.42% | `python` | `_PyObject_Malloc` | memory |
| 2.63% | `python` | `_PyObject_Free` | memory |
| 1.57% | `python` | `PyErr_CheckSignals` | exceptions |
| 1.04% | `python` | `subtype_traverse` | gc |
| 0.88% | `math.cpython-313-x86_64-linux-gnu.so` | `factorial_partial_product` | library |
| 0.85% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 0.84% | `python` | `initialize_locals` | interpreter |
| 0.77% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 0.71% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.67% | `python` | `_PyLong_New` | memory |
| 0.64% | `python` | `set_traverse` | gc |
| 0.63% | `python` | `_PyObject_GetMethod` | dynamic |
| 0.63% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.62% | `python` | `_PyType_Lookup` | lookup |
| 0.61% | `python` | `PyThread_get_thread_ident` | unknown |
| 0.60% | `python` | `_Py_dict_lookup` | lookup |
| 0.51% | `python` | `_PyFrame_Traverse` | interpreter |

## async_tree_io

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 29.15% | `python` | `gc_collect_main` | gc |
| 19.21% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 8.09% | `python` | `visit_reachable` | gc |
| 7.42% | `python` | `visit_decref` | gc |
| 1.89% | `python` | `_PyObject_Malloc` | memory |
| 1.48% | `python` | `subtype_traverse` | gc |
| 1.21% | `python` | `_PyObject_Free` | memory |
| 1.20% | `python` | `initialize_locals` | interpreter |
| 0.95% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 0.79% | `python` | `_PyType_Lookup` | lookup |
| 0.75% | `python` | `_PyFrame_Traverse` | interpreter |
| 0.65% | `python` | `gen_traverse` | gc |
| 0.62% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.60% | `python` | `_Py_dict_lookup` | lookup |
| 0.57% | `python` | `_PyObject_GetMethod` | dynamic |
| 0.56% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 0.54% | `python` | `_PyEval_Vector` | interpreter |
| 0.54% | `python` | `unicodekeys_lookup_unicode` | lookup |

## async_tree_io_tg

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 32.13% | `python` | `gc_collect_main` | gc |
| 17.68% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 8.30% | `python` | `visit_reachable` | gc |
| 7.50% | `python` | `visit_decref` | gc |
| 1.77% | `python` | `_PyObject_Malloc` | memory |
| 1.39% | `python` | `subtype_traverse` | gc |
| 1.15% | `python` | `_PyObject_Free` | memory |
| 1.10% | `python` | `initialize_locals` | interpreter |
| 0.95% | `python` | `_PyFrame_Traverse` | interpreter |
| 0.88% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 0.83% | `python` | `gen_traverse` | gc |
| 0.69% | `python` | `_PyEval_Vector` | interpreter |
| 0.65% | `python` | `set_traverse` | gc |
| 0.65% | `python` | `_PyType_Lookup` | lookup |
| 0.60% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.56% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 0.53% | `python` | `_PyObject_GetMethod` | dynamic |
| 0.53% | `python` | `_Py_dict_lookup` | lookup |
| 0.53% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.51% | `python` | `PyObject_GC_UnTrack` | gc |

## async_tree_memoization

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 22.79% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 20.34% | `python` | `gc_collect_main` | gc |
| 6.26% | `python` | `visit_decref` | gc |
| 6.24% | `python` | `visit_reachable` | gc |
| 2.40% | `python` | `_PyObject_Malloc` | memory |
| 1.54% | `python` | `_PyObject_Free` | memory |
| 1.43% | `python` | `subtype_traverse` | gc |
| 1.16% | `python` | `initialize_locals` | interpreter |
| 1.15% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.11% | `python` | `_PyType_Lookup` | lookup |
| 1.01% | `python` | `_Py_dict_lookup` | lookup |
| 0.94% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.90% | `python` | `_PyObject_GetMethod` | dynamic |
| 0.75% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.73% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 0.63% | `python` | `tupledealloc` | memory |
| 0.56% | `python` | `_PyEval_Vector` | interpreter |
| 0.55% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.55% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.53% | `_asyncio.cpython-313-x86_64-linux-gnu.so` | `TaskObj_traverse` | library |
| 0.52% | `python` | `context_tp_dealloc` | memory |

## async_tree_memoization_tg

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 24.83% | `python` | `gc_collect_main` | gc |
| 20.75% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 6.85% | `python` | `visit_reachable` | gc |
| 6.54% | `python` | `visit_decref` | gc |
| 2.41% | `python` | `_PyObject_Malloc` | memory |
| 1.47% | `python` | `_PyObject_Free` | memory |
| 1.34% | `python` | `subtype_traverse` | gc |
| 1.09% | `python` | `initialize_locals` | interpreter |
| 1.00% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 0.88% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.86% | `python` | `set_traverse` | gc |
| 0.85% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.81% | `python` | `_PyObject_GetMethod` | dynamic |
| 0.81% | `python` | `_PyType_Lookup` | lookup |
| 0.78% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 0.77% | `python` | `_Py_dict_lookup` | lookup |
| 0.68% | `python` | `_PyFrame_Traverse` | interpreter |
| 0.58% | `python` | `gen_traverse` | gc |
| 0.58% | `python` | `_PyEval_Vector` | interpreter |
| 0.57% | `python` | `PyObject_GenericGetAttr` | dynamic |
| 0.56% | `_asyncio.cpython-313-x86_64-linux-gnu.so` | `TaskObj_traverse` | library |
| 0.53% | `python` | `tupledealloc` | memory |
| 0.50% | `python` | `_PyEvalFramePushAndInit` | interpreter |

## async_tree_tg

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 23.33% | `python` | `gc_collect_main` | gc |
| 20.43% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 6.43% | `python` | `visit_reachable` | gc |
| 5.99% | `python` | `visit_decref` | gc |
| 2.68% | `python` | `_PyObject_Malloc` | memory |
| 1.63% | `python` | `_PyObject_Free` | memory |
| 1.25% | `python` | `initialize_locals` | interpreter |
| 1.18% | `python` | `subtype_traverse` | gc |
| 1.07% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.00% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 0.95% | `python` | `_PyObject_GetMethod` | dynamic |
| 0.93% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.90% | `python` | `set_traverse` | gc |
| 0.90% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 0.87% | `python` | `_Py_dict_lookup` | lookup |
| 0.87% | `python` | `_PyType_Lookup` | lookup |
| 0.70% | `python` | `_PyFrame_Traverse` | interpreter |
| 0.60% | `python` | `tupledealloc` | memory |
| 0.59% | `_asyncio.cpython-313-x86_64-linux-gnu.so` | `TaskObj_traverse` | library |
| 0.57% | `python` | `PyObject_GenericGetAttr` | dynamic |
| 0.56% | `python` | `subtype_dealloc` | memory |
| 0.55% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.55% | `python` | `gen_traverse` | gc |

## asyncio_tcp

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 30.17% | `[kernel.kallsyms]` | `copy_user_enhanced_fast_string` | kernel |
| 17.65% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 10.94% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 8.04% | `[kernel.kallsyms]` | `clear_page_erms` | kernel |
| 0.74% | `python` | `_PyObject_Malloc` | memory |
| 0.61% | `[kernel.kallsyms]` | `tcp_sendmsg_locked` | kernel |
| 0.52% | `python` | `unicodekeys_lookup_unicode` | lookup |

## asyncio_tcp_ssl

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 37.26% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 26.21% | `libcrypto.so.1.1` | `CRYPTO_secure_actual_size` | libc |
| 11.69% | `[kernel.kallsyms]` | `copy_user_enhanced_fast_string` | kernel |
| 4.65% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 2.89% | `[kernel.kallsyms]` | `clear_page_erms` | kernel |
| 0.85% | `libssl.so.1.1` | `SSL_rstate_string` | library |
| 0.56% | `libc-2.31.so` | `pthread_attr_setschedparam` | libc |

## asyncio_websockets

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 63.77% | `libz.so.1.2.11` | `crc32_combine64` | library |
| 20.13% | `libz.so.1.2.11` | `inflateBackEnd` | library |
| 2.79% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 2.02% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 0.50% | `python` | `unicodekeys_lookup_unicode` | lookup |

## chameleon

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 40.56% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 3.78% | `python` | `_PyObject_Malloc` | memory |
| 2.93% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 2.53% | `python` | `_PyObject_Free` | memory |
| 1.93% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.90% | `python` | `_Py_dict_lookup` | lookup |
| 1.89% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 1.64% | `python` | `sre_ucs2_charset.isra.0` | library |
| 1.63% | `python` | `_PyUnicode_JoinArray.part.0` | str |
| 1.51% | `python` | `gc_collect_main` | gc |
| 1.15% | `python` | `long_to_decimal_string_internal` | int |
| 0.99% | `python` | `PyUnicode_Format` | str |
| 0.94% | `python` | `_sre_SRE_Pattern_search` | library |
| 0.93% | `python` | `insertdict` | dict |
| 0.79% | `python` | `list_append` | list |
| 0.79% | `python` | `_copy_characters.part.0.constprop.0` | str |
| 0.76% | `python` | `visit_decref` | gc |
| 0.72% | `python` | `dict_get` | dict |
| 0.62% | `python` | `visit_reachable` | gc |
| 0.60% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.58% | `python` | `resize_compact` | str |
| 0.55% | `python` | `_PyObject_Realloc` | memory |
| 0.54% | `python` | `tupledealloc` | memory |
| 0.50% | `libc-2.31.so` | `malloc` | libc |

## chaos

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 51.37% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 2.04% | `python` | `_PyObject_Free` | memory |
| 2.02% | `python` | `_PyObject_Malloc` | memory |
| 1.71% | `python` | `_PyLong_Subtract` | int |
| 1.71% | `python` | `PyType_IsSubtype` | dynamic |
| 1.51% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.26% | `python` | `_PyLong_Add` | int |
| 1.16% | `python` | `PyLong_AsDouble` | int |
| 1.14% | `python` | `float_div` | float |
| 1.07% | `python` | `PyFloat_FromDouble` | float |
| 1.02% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 1.02% | `python` | `float_dealloc` | memory |
| 0.95% | `python` | `compute_range_length` | unknown |
| 0.94% | `python` | `float_richcompare` | float |
| 0.85% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.84% | `python` | `gc_collect_main` | gc |
| 0.84% | `python` | `range_iter` | unknown |
| 0.81% | `python` | `float_sub` | float |
| 0.72% | `libm-2.31.so` | `f64xsubf128` | library |
| 0.70% | `python` | `subtype_dealloc` | memory |
| 0.68% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.60% | `python` | `_PyType_NewManagedObject` | memory |
| 0.60% | `python` | `_PyFloat_ExactDealloc` | memory |
| 0.53% | `python` | `PyLong_FromLong` | int |
| 0.53% | `python` | `_Py_NewReference` | memory |
| 0.50% | `python` | `PyNumber_TrueDivide` | dynamic |

## comprehensions

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 41.43% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 5.29% | `python` | `_Py_dict_lookup` | lookup |
| 2.86% | `python` | `_PyObject_Malloc` | memory |
| 2.34% | `python` | `_PyObject_Free` | memory |
| 1.75% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.53% | `python` | `gc_collect_main` | gc |
| 1.47% | `python` | `dict_get` | dict |
| 1.30% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 1.27% | `python` | `PyObject_RichCompareBool` | dynamic |
| 1.12% | `python` | `PyDict_GetItemRef` | dict |
| 1.12% | `python` | `_PyObject_Realloc` | memory |
| 0.98% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 0.97% | `python` | `insertdict` | dict |
| 0.95% | `python` | `list_dealloc` | memory |
| 0.85% | `python` | `PyObject_Hash` | dynamic |
| 0.81% | `python` | `visit_decref` | gc |
| 0.76% | `python` | `tupledealloc` | memory |
| 0.75% | `python` | `PyFunction_NewWithQualName` | memory |
| 0.73% | `python` | `_PyType_Lookup` | lookup |
| 0.66% | `python` | `long_richcompare` | int |
| 0.63% | `python` | `visit_reachable` | gc |
| 0.61% | `python` | `PyObject_GC_Del` | gc |
| 0.58% | `python` | `_PyList_AppendTakeRefListResize` | list |
| 0.55% | `python` | `_PyObject_GC_New` | gc |
| 0.53% | `python` | `long_hash` | int |
| 0.51% | `python` | `unsafe_tuple_compare` | unknown |

## concurrent_imap

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 25.20% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 2.03% | `python` | `_PyObject_Malloc` | memory |
| 1.74% | `python` | `_PyObject_Free` | memory |
| 1.70% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.33% | `python` | `tupledealloc` | memory |
| 1.20% | `python` | `_PyType_Lookup` | lookup |
| 1.16% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.12% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 0.94% | `[kernel.kallsyms]` | `zap_pte_range.isra.0` | kernel |
| 0.92% | `python` | `initialize_locals` | interpreter |
| 0.72% | `libc-2.31.so` | `pthread_attr_setschedparam` | libc |
| 0.63% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.63% | `python` | `PyObject_GenericGetAttr` | dynamic |
| 0.62% | `python` | `_Py_dict_lookup` | lookup |
| 0.60% | `python` | `gc_collect_main` | gc |
| 0.59% | `python` | `subtype_dealloc` | memory |
| 0.54% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.53% | `python` | `PyObject_GetAttr` | dynamic |
| 0.52% | `python` | `tuple_alloc` | memory |
| 0.50% | `[kernel.kallsyms]` | `copy_page` | kernel |

## coroutines

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 43.25% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 5.18% | `python` | `gen_dealloc` | memory |
| 3.38% | `python` | `_PyObject_Malloc` | memory |
| 3.34% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 3.09% | `python` | `make_gen` | unknown |
| 2.88% | `python` | `_PyObject_Free` | memory |
| 2.79% | `python` | `_PyObject_GC_NewVar` | gc |
| 1.95% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.87% | `python` | `_PyLong_Subtract` | int |
| 1.67% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 1.40% | `python` | `_PyLong_Add` | int |
| 1.34% | `python` | `PyObject_CallFinalizerFromDealloc` | memory |
| 1.28% | `python` | `gc_collect_main` | gc |
| 1.25% | `python` | `PyObject_GC_Del` | gc |
| 1.17% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.05% | `python` | `_PyObject_GC_Link` | gc |
| 0.97% | `python` | `_PyCoro_GetAwaitableIter` | unknown |
| 0.79% | `python` | `_Py_MakeCoro` | unknown |
| 0.79% | `python` | `_PyFrame_Copy` | unknown |
| 0.66% | `python` | `visit_decref` | gc |
| 0.56% | `python` | `visit_reachable` | gc |
| 0.56% | `python` | `_PyThreadState_PopFrame` | interpreter |
| 0.53% | `python` | `_Py_dict_lookup` | lookup |

## coverage

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 15.76% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 6.22% | `python` | `call_instrumentation_vector.part.0` | unknown |
| 5.86% | `tracer.cpython-313-x86_64-linux-gnu.so` | `CTracer_trace` | library |
| 5.00% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 2.87% | `python` | `_Py_call_instrumentation_line` | unknown |
| 2.73% | `python` | `_Py_dict_lookup` | lookup |
| 2.54% | `python` | `siphash13` | str |
| 2.50% | `python` | `_PyObject_Malloc` | memory |
| 2.40% | `python` | `_PyObject_Free` | memory |
| 1.70% | `python` | `PyLong_FromLong` | int |
| 1.69% | `python` | `gc_collect_main` | gc |
| 1.62% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 1.45% | `python` | `PyDict_GetItem` | dict |
| 1.36% | `python` | `_PyObject_GenericSetAttrWithDict` | dynamic |
| 1.11% | `python` | `set_add_entry` | miscobj |
| 0.93% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 0.90% | `python` | `visit_decref` | gc |
| 0.89% | `python` | `_Py_hashtable_get_entry_generic` | unknown |
| 0.84% | `python` | `_PyType_Lookup` | lookup |
| 0.78% | `python` | `_PyUnicode_InternInPlace` | str |
| 0.76% | `python` | `frame_dealloc` | memory |
| 0.76% | `python` | `visit_reachable` | gc |
| 0.75% | `python` | `unicode_decode_utf8` | str |
| 0.74% | `python` | `PySet_Add` | unknown |
| 0.68% | `python` | `_PyObject_GC_NewVar` | gc |
| 0.65% | `python` | `ascii_decode` | str |
| 0.63% | `python` | `PyObject_Hash` | dynamic |
| 0.63% | `python` | `PyUnicode_New.part.0` | memory |
| 0.62% | `python` | `_Py_call_instrumentation_jump` | unknown |
| 0.60% | `python` | `PyDict_SetDefault` | dict |
| 0.59% | `python` | `PyObject_GC_Del` | gc |
| 0.55% | `python` | `sys_trace_return` | unknown |
| 0.52% | `python` | `sys_trace_start` | unknown |
| 0.51% | `python` | `_PyCode_GetCode` | unknown |
| 0.50% | `python` | `r_object` | import |

## crypto_pyaes

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 39.17% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 6.62% | `python` | `_PyObject_Free` | memory |
| 5.61% | `python` | `_PyObject_Malloc` | memory |
| 5.59% | `python` | `long_bitwise` | int |
| 3.12% | `python` | `l_mod` | int |
| 2.94% | `python` | `long_rshift1` | int |
| 2.24% | `python` | `_PyLong_New` | memory |
| 1.53% | `python` | `long_and` | int |
| 1.49% | `python` | `long_rshift` | int |
| 1.37% | `python` | `PyNumber_And` | dynamic |
| 1.15% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 1.10% | `python` | `long_xor` | int |
| 1.00% | `python` | `PyNumber_Xor` | dynamic |
| 1.00% | `python` | `PyLong_FromLong` | int |
| 0.97% | `python` | `long_dealloc` | memory |
| 0.96% | `python` | `_PyLong_Add` | int |
| 0.87% | `python` | `gc_collect_main` | gc |
| 0.86% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.74% | `python` | `_Py_NewReference` | memory |
| 0.69% | `python` | `PyNumber_Rshift` | dynamic |
| 0.69% | `python` | `PyNumber_Remainder` | dynamic |
| 0.62% | `python` | `long_mod` | int |
| 0.54% | `python` | `list_dealloc` | memory |
| 0.50% | `python` | `_Py_dict_lookup` | lookup |

## dask

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 25.20% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 4.98% | `python` | `gc_collect_main` | gc |
| 2.77% | `python` | `_PyObject_Malloc` | memory |
| 2.48% | `python` | `visit_decref` | gc |
| 2.42% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 2.24% | `python` | `_PyObject_Free` | memory |
| 1.94% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 1.93% | `python` | `visit_reachable` | gc |
| 1.47% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.44% | `python` | `tupledealloc` | memory |
| 1.36% | `python` | `_Py_dict_lookup` | lookup |
| 1.06% | `python` | `initialize_locals` | interpreter |
| 0.92% | `python` | `_PyType_Lookup` | lookup |
| 0.80% | `python` | `PyBytes_Repr` | str |
| 0.70% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.58% | `python` | `dict_dealloc` | memory |
| 0.52% | `python` | `insertdict` | dict |
| 0.52% | `python` | `tuple_alloc` | memory |

## deepcopy

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 45.38% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 4.85% | `python` | `_Py_dict_lookup` | lookup |
| 3.20% | `python` | `_PyObject_Malloc` | memory |
| 3.03% | `python` | `_PyObject_Free` | memory |
| 2.76% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.93% | `python` | `dict_get` | dict |
| 1.17% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.08% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.99% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 0.90% | `python` | `sys_audit_tstate` | unknown |
| 0.82% | `python` | `_PyLong_New` | memory |
| 0.80% | `python` | `long_hash` | int |
| 0.78% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 0.77% | `python` | `initialize_locals` | interpreter |
| 0.73% | `python` | `gc_collect_main` | gc |
| 0.69% | `python` | `PySys_Audit` | unknown |
| 0.66% | `python` | `PyLong_FromVoidPtr` | int |
| 0.66% | `python` | `tupledealloc` | memory |
| 0.63% | `python` | `list_append` | list |
| 0.62% | `python` | `insertdict` | dict |
| 0.62% | `python` | `_PyType_Lookup` | lookup |
| 0.58% | `python` | `PyObject_RichCompareBool` | dynamic |
| 0.57% | `python` | `_PyObject_Realloc` | memory |

## deltablue

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 63.84% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 2.57% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.87% | `python` | `gc_collect_main` | gc |
| 1.84% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 1.63% | `python` | `_PyObject_Malloc` | memory |
| 1.44% | `python` | `_PyObject_Free` | memory |
| 1.32% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.21% | `python` | `_PyType_Lookup` | lookup |
| 0.99% | `python` | `_PyObject_GetMethod` | dynamic |
| 0.87% | `python` | `visit_decref` | gc |
| 0.74% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 0.69% | `python` | `_PyThreadState_PopFrame` | interpreter |
| 0.56% | `python` | `visit_reachable` | gc |
| 0.50% | `python` | `_Py_dict_lookup` | lookup |

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
| 0.53% | `python` | `r_object` | import |
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
| 0.62% | `python` | `update_one_slot` | lookup |
| 0.62% | `python` | `_PyPegen_is_memoized` | interpreter |
| 0.55% | `python` | `insertdict` | dict |
| 0.52% | `python` | `_PyFrame_ClearExceptCode` | interpreter |

## docutils

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 27.04% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 6.46% | `python` | `sre_ucs1_match` | library |
| 5.80% | `python` | `gc_collect_main` | gc |
| 3.27% | `python` | `_PyObject_Malloc` | memory |
| 3.10% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 2.59% | `python` | `_PyObject_Free` | memory |
| 2.38% | `python` | `_PyType_Lookup` | lookup |
| 2.06% | `python` | `visit_decref` | gc |
| 2.02% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 1.54% | `python` | `sre_ucs2_charset.isra.0` | library |
| 1.49% | `python` | `_Py_dict_lookup` | lookup |
| 1.40% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.38% | `python` | `PyObject_GenericGetAttr` | dynamic |
| 1.26% | `python` | `visit_reachable` | gc |
| 1.21% | `python` | `list_dealloc` | memory |
| 0.84% | `python` | `tupledealloc` | memory |
| 0.75% | `python` | `_PyObject_GetInstanceAttribute` | dynamic |
| 0.73% | `python` | `PyObject_GetAttr` | dynamic |
| 0.66% | `python` | `initialize_locals` | interpreter |
| 0.63% | `libc-2.31.so` | `pthread_attr_setschedparam` | libc |
| 0.61% | `python` | `PyType_IsSubtype` | dynamic |
| 0.57% | `python` | `list_traverse` | gc |
| 0.55% | `python` | `_PyObject_GetMethod` | dynamic |
| 0.54% | `python` | `list_slice.isra.0` | list |
| 0.53% | `python` | `dict_traverse` | gc |

## dulwich_log

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 29.78% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 3.41% | `python` | `_PyObject_Malloc` | memory |
| 2.51% | `libz.so.1.2.11` | `inflateCodesUsed` | library |
| 2.46% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 2.45% | `python` | `_PyObject_Free` | memory |
| 1.50% | `libz.so.1.2.11` | `inflateBackEnd` | library |
| 1.27% | `libz.so.1.2.11` | `inflate` | library |
| 1.21% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.17% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.13% | `python` | `gc_collect_main` | gc |
| 1.06% | `python` | `tupledealloc` | memory |
| 0.70% | `python` | `_Py_dict_lookup` | lookup |
| 0.68% | `libc-2.31.so` | `pthread_attr_setschedparam` | libc |
| 0.67% | `python` | `_PyType_Lookup` | lookup |
| 0.66% | `python` | `visit_decref` | gc |
| 0.52% | `python` | `initialize_locals` | interpreter |

## fannkuch

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 40.39% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 7.48% | `python` | `PySlice_AdjustIndices` | miscobj |
| 5.68% | `python` | `list_ass_slice` | list |
| 4.54% | `python` | `list_subscript` | list |
| 3.41% | `python` | `list_dealloc` | memory |
| 3.04% | `python` | `_PyBuildSlice_ConsumeRefs` | miscobj |
| 2.91% | `python` | `_PyObject_Free` | memory |
| 2.76% | `python` | `_PyEval_SliceIndex` | interpreter |
| 2.22% | `python` | `slice_dealloc` | memory |
| 2.16% | `python` | `PySlice_New` | memory |
| 2.07% | `python` | `PyNumber_AsSsize_t` | dynamic |
| 1.89% | `python` | `_PyLong_Add` | int |
| 1.86% | `python` | `_PyObject_Malloc` | memory |
| 1.77% | `python` | `PySlice_Unpack` | miscobj |
| 1.69% | `python` | `_Py_NewReference` | memory |
| 1.42% | `python` | `list_ass_subscript` | list |
| 1.30% | `python` | `PyLong_AsSsize_t` | int |
| 0.99% | `python` | `PyObject_GetItem` | dynamic |
| 0.95% | `python` | `list_insert` | list |
| 0.68% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 0.60% | `python` | `_PyLong_Subtract` | int |
| 0.59% | `python` | `_PyTrash_end` | gc |
| 0.51% | `python` | `list_pop` | list |
| 0.50% | `python` | `PyObject_SetItem` | dynamic |

## float

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 37.69% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 3.73% | `python` | `gc_collect_main` | gc |
| 3.19% | `libm-2.31.so` | `f64xsubf128` | library |
| 2.78% | `python` | `_PyObject_Malloc` | memory |
| 2.52% | `python` | `visit_decref` | gc |
| 2.45% | `python` | `subtype_traverse` | gc |
| 2.28% | `python` | `visit_reachable` | gc |
| 1.84% | `python` | `_PyObject_Free` | memory |
| 1.61% | `python` | `float_div` | float |
| 1.43% | `python` | `PyFloat_FromDouble` | float |
| 1.30% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.27% | `python` | `subtype_dealloc` | memory |
| 1.19% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.11% | `python` | `float_dealloc` | memory |
| 0.92% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 0.81% | `python` | `tupledealloc` | memory |
| 0.75% | `python` | `PyType_IsSubtype` | dynamic |
| 0.74% | `python` | `_Py_NewReference` | memory |
| 0.71% | `python` | `initialize_locals` | interpreter |
| 0.66% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.59% | `python` | `_PyType_Lookup` | lookup |
| 0.56% | `python` | `_Py_Dealloc` | memory |
| 0.51% | `python` | `_Py_dict_lookup` | lookup |
| 0.50% | `python` | `PyType_GenericAlloc` | memory |

## gc_collect

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 28.19% | `python` | `gc_collect_main` | gc |
| 13.49% | `python` | `visit_reachable` | gc |
| 12.70% | `python` | `visit_decref` | gc |
| 8.77% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 4.17% | `python` | `dict_traverse` | gc |
| 1.74% | `python` | `PyObject_VisitManagedDict` | dynamic |
| 1.71% | `python` | `func_traverse` | gc |
| 1.66% | `python` | `PyObject_IS_GC` | gc |
| 1.49% | `python` | `_PyDict_MaybeUntrack` | gc |
| 1.39% | `python` | `subtype_traverse` | gc |
| 1.39% | `python` | `set_traverse` | gc |
| 1.28% | `python` | `_PyObject_Malloc` | memory |
| 1.11% | `python` | `type_is_gc` | gc |
| 0.99% | `python` | `_PyObject_Free` | memory |
| 0.75% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.74% | `python` | `tupletraverse` | tuple |
| 0.73% | `python` | `type_traverse` | gc |
| 0.63% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 0.55% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 0.53% | `python` | `list_traverse` | gc |

## gc_traversal

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 28.52% | `python` | `visit_reachable` | gc |
| 19.43% | `python` | `visit_decref` | gc |
| 15.53% | `python` | `list_traverse` | gc |
| 11.00% | `python` | `gc_collect_main` | gc |
| 6.13% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 1.72% | `python` | `dict_traverse` | gc |
| 0.79% | `python` | `_PyObject_Malloc` | memory |
| 0.69% | `python` | `func_traverse` | gc |
| 0.68% | `python` | `PyObject_IS_GC` | gc |
| 0.66% | `python` | `_PyObject_Free` | memory |
| 0.60% | `python` | `_PyDict_MaybeUntrack` | gc |
| 0.59% | `python` | `set_traverse` | gc |
| 0.59% | `python` | `unicodekeys_lookup_unicode` | lookup |

## generators

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 48.82% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 4.51% | `python` | `gc_collect_main` | gc |
| 3.67% | `python` | `_PyObject_Malloc` | memory |
| 2.67% | `python` | `_PyObject_Free` | memory |
| 1.56% | `python` | `visit_reachable` | gc |
| 1.38% | `python` | `visit_decref` | gc |
| 1.38% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 1.18% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.14% | `python` | `gen_dealloc` | memory |
| 1.05% | `python` | `PyObject_RichCompareBool` | dynamic |
| 1.02% | `python` | `initialize_locals` | interpreter |
| 0.90% | `python` | `long_add` | int |
| 0.88% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.84% | `python` | `PyObject_VisitManagedDict` | dynamic |
| 0.81% | `python` | `subtype_traverse` | gc |
| 0.79% | `python` | `_PyObject_GC_NewVar` | gc |
| 0.73% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.73% | `python` | `compute_range_length` | unknown |
| 0.73% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.71% | `python` | `range_subscript` | unknown |
| 0.63% | `python` | `make_gen` | unknown |
| 0.62% | `python` | `_PyType_Lookup` | lookup |
| 0.59% | `python` | `PyNumber_Add` | dynamic |
| 0.53% | `python` | `long_richcompare` | int |

## genshi

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 43.47% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 3.18% | `python` | `_PyObject_Malloc` | memory |
| 2.53% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 2.30% | `python` | `_PyObject_Free` | memory |
| 2.19% | `python` | `_Py_dict_lookup` | lookup |
| 1.28% | `python` | `gc_collect_main` | gc |
| 1.24% | `python` | `tupledealloc` | memory |
| 1.23% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.17% | `python` | `insertdict` | dict |
| 1.12% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 1.01% | `python` | `_PyType_Lookup` | lookup |
| 0.74% | `python` | `_PyTuple_FromArraySteal` | tuple |
| 0.68% | `python` | `_PyObject_GC_New` | gc |
| 0.68% | `libc-2.31.so` | `pthread_attr_setschedparam` | libc |
| 0.63% | `python` | `_PyObject_GetMethod` | dynamic |
| 0.63% | `python` | `visit_decref` | gc |
| 0.60% | `python` | `PyDict_GetItemRef` | dict |
| 0.59% | `python` | `_PyDict_FromItems` | dict |
| 0.58% | `python` | `pattern_subx` | library |
| 0.53% | `python` | `free_keys_object` | dict |
| 0.51% | `python` | `visit_reachable` | gc |
| 0.50% | `python` | `tuple_alloc` | memory |

## go

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 63.06% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 2.24% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 2.10% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.88% | `python` | `_PyObject_GetMethod` | dynamic |
| 1.66% | `python` | `_PyObject_Free` | memory |
| 1.35% | `python` | `_PyObject_Malloc` | memory |
| 1.28% | `python` | `_PyType_Lookup` | lookup |
| 1.15% | `python` | `_Py_dict_lookup` | lookup |
| 1.01% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.95% | `python` | `gc_collect_main` | gc |
| 0.92% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 0.73% | `python` | `PyDict_GetItemRef` | dict |
| 0.65% | `python` | `long_bitwise` | int |
| 0.55% | `python` | `insertdict` | dict |
| 0.53% | `python` | `visit_decref` | gc |

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
| 58.98% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 2.88% | `python` | `PyObject_RichCompareBool` | dynamic |
| 2.28% | `python` | `list_contains` | list |
| 1.90% | `python` | `long_richcompare` | int |
| 1.71% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.43% | `python` | `_PyObject_Malloc` | memory |
| 1.26% | `python` | `_PyObject_Free` | memory |
| 1.25% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 1.04% | `python` | `gen_iternext` | unknown |
| 1.01% | `python` | `gc_collect_main` | gc |
| 1.00% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.94% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.56% | `python` | `PyLong_FromLong` | int |
| 0.54% | `python` | `visit_decref` | gc |
| 0.53% | `python` | `builtin_sum` | unknown |
| 0.51% | `python` | `_Py_dict_lookup` | lookup |

## html5lib

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 37.89% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 4.92% | `python` | `sre_ucs2_charset.isra.0` | library |
| 3.22% | `python` | `gc_collect_main` | gc |
| 2.49% | `python` | `_PyObject_Malloc` | memory |
| 2.39% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.96% | `python` | `_PyObject_Free` | memory |
| 1.53% | `python` | `_Py_dict_lookup` | lookup |
| 1.45% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 1.29% | `python` | `visit_decref` | gc |
| 1.25% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 0.94% | `python` | `PyDict_GetItemRef` | dict |
| 0.84% | `python` | `visit_reachable` | gc |
| 0.68% | `python` | `sre_ucs1_count` | library |
| 0.66% | `python` | `tupledealloc` | memory |
| 0.66% | `libc-2.31.so` | `pthread_attr_setschedparam` | libc |
| 0.65% | `python` | `PyObject_RichCompareBool` | dynamic |
| 0.65% | `python` | `_PyType_Lookup` | lookup |
| 0.55% | `python` | `PyObject_GenericGetAttr` | dynamic |
| 0.52% | `python` | `initialize_locals` | interpreter |

## json

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 11.81% | `_json.cpython-313-x86_64-linux-gnu.so` | `scanstring_unicode` | library |
| 8.25% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 6.39% | `_json.cpython-313-x86_64-linux-gnu.so` | `scan_once_unicode` | library |
| 6.04% | `python` | `_PyObject_Malloc` | memory |
| 5.34% | `python` | `siphash13` | str |
| 4.53% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 4.31% | `python` | `_PyObject_Free` | memory |
| 2.99% | `python` | `PyDict_SetDefault` | dict |
| 2.69% | `python` | `insertdict` | dict |
| 2.61% | `python` | `_Py_dict_lookup` | lookup |
| 2.31% | `python` | `PyLong_FromString` | int |
| 2.08% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 2.02% | `python` | `PyUnicode_Substring` | str |
| 1.93% | `libc-2.31.so` | `pthread_attr_setschedparam` | libc |
| 1.70% | `python` | `free_keys_object` | dict |
| 1.66% | `python` | `PyUnicode_New.part.0` | memory |
| 1.42% | `python` | `find_empty_slot` | dict |
| 1.21% | `python` | `build_indices_unicode` | dict |
| 0.90% | `python` | `PyObject_IS_GC` | gc |
| 0.86% | `python` | `PyDict_SetItem` | dict |
| 0.82% | `python` | `gc_collect_main` | gc |
| 0.78% | `python` | `_sre_SRE_Pattern_match` | library |
| 0.63% | `python` | `tupledealloc` | memory |
| 0.61% | `python` | `sre_ucs1_match` | library |
| 0.58% | `python` | `new_keys_object` | dict |
| 0.58% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 0.57% | `python` | `unicode_dealloc` | memory |
| 0.56% | `python` | `initialize_locals` | interpreter |
| 0.54% | `python` | `_Py_NewReference` | memory |

## json_dumps

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 14.37% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 6.45% | `_json.cpython-313-x86_64-linux-gnu.so` | `py_encode_basestring_ascii` | library |
| 6.37% | `python` | `_PyObject_Malloc` | memory |
| 4.55% | `python` | `_PyObject_Free` | memory |
| 3.52% | `python` | `_copy_characters.part.0.constprop.0` | str |
| 3.31% | `python` | `_PyUnicodeWriter_WriteStr` | str |
| 2.60% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 2.47% | `_json.cpython-313-x86_64-linux-gnu.so` | `encoder_listencode_obj` | library |
| 2.47% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 2.45% | `python` | `_Py_dict_lookup` | lookup |
| 2.19% | `python` | `resize_compact` | str |
| 1.99% | `python` | `PyUnicode_New` | memory |
| 1.74% | `python` | `vgetargskeywords.constprop.0` | calls |
| 1.55% | `_json.cpython-313-x86_64-linux-gnu.so` | `encoder_encode_key_value` | library |
| 1.34% | `python` | `gc_collect_main` | gc |
| 1.25% | `python` | `tupledealloc` | memory |
| 1.09% | `python` | `convertitem.constprop.0` | unknown |
| 1.05% | `python` | `PyDict_Next` | dict |
| 1.03% | `python` | `PyDict_GetItemRef` | dict |
| 0.94% | `python` | `_PyObject_Realloc` | memory |
| 0.92% | `python` | `_PyUnicodeWriter_PrepareInternal` | str |
| 0.88% | `python` | `initialize_locals` | interpreter |
| 0.87% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 0.68% | `python` | `_PyType_Lookup` | lookup |
| 0.66% | `python` | `visit_decref` | gc |
| 0.64% | `python` | `long_to_decimal_string_internal` | int |
| 0.64% | `python` | `_Py_Dealloc` | memory |
| 0.64% | `python` | `unicode_dealloc` | memory |
| 0.54% | `python` | `visit_reachable` | gc |
| 0.52% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.50% | `python` | `_Py_NewReference` | memory |

## json_loads

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 13.31% | `_json.cpython-313-x86_64-linux-gnu.so` | `scanstring_unicode` | library |
| 7.07% | `_json.cpython-313-x86_64-linux-gnu.so` | `scan_once_unicode` | library |
| 6.60% | `python` | `_PyObject_Malloc` | memory |
| 6.37% | `python` | `siphash13` | str |
| 6.28% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 5.86% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 4.99% | `python` | `_PyObject_Free` | memory |
| 3.07% | `python` | `PyUnicode_Substring` | str |
| 2.89% | `python` | `insertdict` | dict |
| 2.89% | `python` | `_Py_dict_lookup` | lookup |
| 2.53% | `python` | `PyUnicode_New.part.0` | memory |
| 2.47% | `python` | `PyDict_SetDefault` | dict |
| 2.43% | `python` | `PyLong_FromString` | int |
| 2.40% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 1.23% | `python` | `find_empty_slot` | dict |
| 0.99% | `python` | `free_keys_object` | dict |
| 0.97% | `libc-2.31.so` | `pthread_attr_setschedparam` | libc |
| 0.95% | `python` | `gc_collect_main` | gc |
| 0.87% | `python` | `PyDict_SetItem` | dict |
| 0.85% | `python` | `build_indices_unicode` | dict |
| 0.72% | `python` | `PyObject_IS_GC` | gc |
| 0.71% | `python` | `unicode_dealloc` | memory |
| 0.54% | `python` | `_Py_NewReference` | memory |

## logging

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 45.45% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 3.26% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 2.13% | `python` | `initialize_locals` | interpreter |
| 2.04% | `python` | `_PyObject_Malloc` | memory |
| 1.77% | `python` | `_Py_dict_lookup` | lookup |
| 1.72% | `python` | `_PyObject_Free` | memory |
| 1.53% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 1.53% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 1.36% | `python` | `dict_dealloc` | memory |
| 1.34% | `python` | `PyCode_Addr2Line` | exceptions |
| 1.23% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 1.01% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.95% | `python` | `PyDict_New` | memory |
| 0.89% | `python` | `PyDict_GetItemRef` | dict |
| 0.86% | `python` | `_PyType_Lookup` | lookup |
| 0.76% | `python` | `_Py_NewReference` | memory |
| 0.74% | `python` | `tupledealloc` | memory |
| 0.67% | `python` | `_PyTrash_end` | gc |
| 0.65% | `python` | `PyObject_GenericGetAttr` | dynamic |
| 0.60% | `python` | `_PyThreadState_PopFrame` | interpreter |
| 0.57% | `python` | `gc_collect_main` | gc |
| 0.57% | `python` | `PyUnicode_Contains` | str |
| 0.53% | `python` | `PyObject_GetAttr` | dynamic |

## mako

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 37.49% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 6.61% | `python` | `replace` | str |
| 3.49% | `python` | `_PyObject_Malloc` | memory |
| 3.20% | `python` | `long_to_decimal_string_internal` | int |
| 2.76% | `python` | `_PyObject_Free` | memory |
| 2.71% | `python` | `_PyUnicode_JoinArray.part.0` | str |
| 2.17% | `python` | `unicode_replace` | str |
| 2.00% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 1.52% | `python` | `deque_append` | miscobj |
| 1.50% | `python` | `dequeiter_next` | miscobj |
| 1.39% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.38% | `python` | `gc_collect_main` | gc |
| 0.86% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 0.84% | `python` | `list_extend` | list |
| 0.79% | `python` | `visit_decref` | gc |
| 0.75% | `python` | `list_dealloc` | memory |
| 0.66% | `python` | `PyErr_CheckSignals` | exceptions |
| 0.65% | `python` | `PyUnicode_New` | memory |
| 0.64% | `libc-2.31.so` | `pthread_attr_setschedparam` | libc |
| 0.64% | `python` | `sre_ucs2_charset.isra.0` | library |
| 0.61% | `python` | `_Py_dict_lookup` | lookup |
| 0.59% | `python` | `deque_clear.part.0` | miscobj |
| 0.54% | `python` | `PyObject_Str` | dynamic |
| 0.52% | `python` | `_PyLong_New` | memory |
| 0.52% | `python` | `visit_reachable` | gc |
| 0.50% | `python` | `_PyEval_FrameClearAndPop` | interpreter |

## mdp

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 26.73% | `python` | `tuplehash` | tuple |
| 17.52% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 13.62% | `python` | `PyObject_Hash` | dynamic |
| 10.06% | `python` | `long_hash` | int |
| 5.75% | `python` | `_Py_dict_lookup` | lookup |
| 2.88% | `python` | `PyObject_RichCompareBool` | dynamic |
| 1.78% | `python` | `tuplerichcompare` | tuple |
| 1.23% | `python` | `_PyObject_Malloc` | memory |
| 1.18% | `python` | `_PyObject_Free` | memory |
| 1.11% | `python` | `dict_subscript` | dict |
| 0.91% | `python` | `_PyLong_GCD` | int |
| 0.79% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 0.73% | `python` | `PyDict_GetItemRef` | dict |
| 0.63% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 0.60% | `python` | `unicodekeys_lookup_unicode` | lookup |

## meteor_contest

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 25.25% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 6.65% | `python` | `set_issubset` | miscobj |
| 6.46% | `python` | `set_lookkey` | miscobj |
| 5.89% | `python` | `setiter_iternext` | miscobj |
| 3.27% | `python` | `set_difference` | miscobj |
| 2.91% | `python` | `set_dealloc` | memory |
| 2.47% | `python` | `_PyObject_Malloc` | memory |
| 2.43% | `python` | `PyObject_RichCompareBool` | dynamic |
| 2.38% | `python` | `_PyObject_Free` | memory |
| 1.69% | `python` | `set_add_entry` | miscobj |
| 1.57% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 1.53% | `python` | `list_dealloc` | memory |
| 1.24% | `python` | `long_richcompare` | int |
| 1.23% | `python` | `list_slice.isra.0` | list |
| 1.20% | `python` | `gc_collect_main` | gc |
| 1.18% | `python` | `min_max` | unknown |
| 1.10% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.96% | `python` | `PyObject_RichCompare` | dynamic |
| 0.90% | `python` | `PyIter_Next` | dynamic |
| 0.80% | `python` | `set_intersection` | miscobj |
| 0.78% | `python` | `set_table_resize` | miscobj |
| 0.67% | `python` | `PyObject_GC_Del` | gc |
| 0.64% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 0.64% | `python` | `visit_decref` | gc |
| 0.62% | `python` | `set_update_internal` | miscobj |
| 0.53% | `python` | `PyType_GenericAlloc` | memory |
| 0.53% | `python` | `tupledealloc` | memory |
| 0.51% | `python` | `_Py_dict_lookup` | lookup |
| 0.51% | `python` | `set_richcompare` | miscobj |

## mypy2

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 31.23% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 13.34% | `python` | `gc_collect_main` | gc |
| 2.82% | `python` | `_PyObject_Malloc` | memory |
| 2.71% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 2.54% | `python` | `visit_decref` | gc |
| 2.23% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 2.00% | `python` | `_PyObject_Free` | memory |
| 1.54% | `python` | `initialize_locals` | interpreter |
| 1.52% | `python` | `_PyType_Lookup` | lookup |
| 1.47% | `python` | `_Py_dict_lookup` | lookup |
| 1.36% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 1.31% | `python` | `subtype_traverse` | gc |
| 1.22% | `python` | `visit_reachable` | gc |
| 1.18% | `python` | `subtype_dealloc` | memory |
| 1.10% | `python` | `PyDict_GetItemRef` | dict |
| 0.93% | `python` | `siphash13` | str |
| 0.87% | `_json.cpython-313-x86_64-linux-gnu.so` | `scanstring_unicode` | library |
| 0.79% | `_json.cpython-313-x86_64-linux-gnu.so` | `scan_once_unicode` | library |
| 0.76% | `python` | `tupledealloc` | memory |
| 0.69% | `python` | `PyType_IsSubtype` | dynamic |
| 0.68% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.67% | `python` | `list_dealloc` | memory |
| 0.57% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.53% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.51% | `python` | `insertdict` | dict |

## nbody

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 63.39% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 4.46% | `python` | `PyFloat_FromDouble` | float |
| 2.88% | `libm-2.31.so` | `f64xsubf128` | library |
| 1.93% | `python` | `float_dealloc` | memory |
| 1.31% | `python` | `float_pow` | float |
| 1.27% | `python` | `_Py_NewReference` | memory |
| 1.17% | `python` | `gc_collect_main` | gc |
| 1.09% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.96% | `python` | `_PyObject_Malloc` | memory |
| 0.85% | `python` | `_PyObject_Free` | memory |
| 0.65% | `python` | `visit_decref` | gc |
| 0.63% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 0.51% | `python` | `_PyFloat_ExactDealloc` | memory |

## nqueens

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 37.86% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 4.02% | `python` | `_PyObject_Malloc` | memory |
| 3.54% | `python` | `_PyObject_Free` | memory |
| 2.02% | `python` | `set_add_entry` | miscobj |
| 1.77% | `python` | `gen_iternext` | unknown |
| 1.61% | `python` | `PySlice_AdjustIndices` | miscobj |
| 1.53% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 1.51% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.25% | `python` | `gc_collect_main` | gc |
| 1.21% | `python` | `_PyBuildSlice_ConsumeRefs` | miscobj |
| 1.18% | `python` | `list_dealloc` | memory |
| 1.03% | `python` | `set_dealloc` | memory |
| 0.88% | `python` | `tupledealloc` | memory |
| 0.84% | `python` | `_Py_dict_lookup` | lookup |
| 0.82% | `python` | `_PyLong_Add` | int |
| 0.81% | `python` | `list_subscript` | list |
| 0.79% | `python` | `_Py_NewReference` | memory |
| 0.73% | `python` | `_PyType_Lookup` | lookup |
| 0.72% | `python` | `PyFunction_NewWithQualName` | memory |
| 0.65% | `python` | `visit_decref` | gc |
| 0.63% | `python` | `set_update_internal` | miscobj |
| 0.60% | `python` | `PyNumber_AsSsize_t` | dynamic |
| 0.56% | `python` | `list_slice.isra.0` | list |
| 0.55% | `python` | `PyObject_GC_Del` | gc |
| 0.54% | `python` | `PyLong_FromLong` | int |
| 0.51% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 0.51% | `python` | `set_table_resize` | miscobj |
| 0.51% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.51% | `python` | `_PyTrash_end` | gc |
| 0.50% | `python` | `visit_reachable` | gc |

## pathlib

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 18.59% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 4.40% | `python` | `_PyObject_Malloc` | memory |
| 4.00% | `python` | `_PyObject_Free` | memory |
| 1.71% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.43% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 1.25% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.22% | `python` | `initialize_locals` | interpreter |
| 1.19% | `[kernel.kallsyms]` | `__d_lookup_rcu` | kernel |
| 1.12% | `libpthread-2.31.so` | `__pthread_mutex_lock` | library |
| 1.07% | `python` | `_PyType_Lookup` | lookup |
| 1.00% | `[kernel.kallsyms]` | `ext4_htree_store_dirent` | kernel |
| 1.00% | `libpthread-2.31.so` | `pthread_mutex_unlock` | library |
| 0.98% | `[kernel.kallsyms]` | `__ext4fs_dirhash` | kernel |
| 0.94% | `python` | `gc_collect_main` | gc |
| 0.89% | `python` | `_Py_dict_lookup` | lookup |
| 0.89% | `[kernel.kallsyms]` | `memset_erms` | kernel |
| 0.78% | `python` | `tupledealloc` | memory |
| 0.76% | `libc-2.31.so` | `pthread_attr_setschedparam` | libc |
| 0.75% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.72% | `python` | `_PyLong_New` | memory |
| 0.67% | `python` | `sre_ucs1_match` | library |
| 0.67% | `python` | `_Py_NewReference` | memory |
| 0.64% | `python` | `PyDict_GetItemRef` | dict |
| 0.62% | `[kernel.kallsyms]` | `strncpy_from_user` | kernel |
| 0.61% | `[kernel.kallsyms]` | `filldir64` | kernel |
| 0.56% | `python` | `subtype_dealloc` | memory |
| 0.55% | `python` | `list_dealloc` | memory |
| 0.55% | `python` | `tuple_alloc` | memory |
| 0.54% | `python` | `k_mul` | int |
| 0.53% | `[kernel.kallsyms]` | `link_path_walk.part.0` | kernel |
| 0.51% | `python` | `_PyEval_FrameClearAndPop` | interpreter |

## pickle

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 23.13% | `_pickle.cpython-313-x86_64-linux-gnu.so` | `save` | library |
| 8.95% | `_pickle.cpython-313-x86_64-linux-gnu.so` | `_Pickler_Write` | library |
| 7.92% | `_pickle.cpython-313-x86_64-linux-gnu.so` | `PyMemoTable_Set` | library |
| 5.47% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 3.74% | `_pickle.cpython-313-x86_64-linux-gnu.so` | `Pickler_clear` | library |
| 3.35% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 3.29% | `_pickle.cpython-313-x86_64-linux-gnu.so` | `memo_put.isra.0` | library |
| 2.57% | `python` | `PyDict_Next` | dict |
| 2.52% | `python` | `PyUnicode_AsUTF8AndSize` | str |
| 2.47% | `_pickle.cpython-313-x86_64-linux-gnu.so` | `_Pickler_Write.constprop.3` | library |
| 1.85% | `python` | `_PyObject_Malloc` | memory |
| 1.69% | `_pickle.cpython-313-x86_64-linux-gnu.so` | `memo_get.isra.0` | library |
| 1.50% | `python` | `_PyObject_Free` | memory |
| 1.48% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.26% | `libc-2.31.so` | `pthread_attr_setschedparam` | libc |
| 1.19% | `python` | `gc_collect_main` | gc |
| 0.86% | `python` | `_Py_dict_lookup` | lookup |
| 0.71% | `python` | `_PyType_Lookup` | lookup |
| 0.56% | `python` | `visit_decref` | gc |
| 0.55% | `python` | `PyLong_AsLongAndOverflow` | int |

## pickle_dict

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 40.52% | `_pickle.cpython-313-x86_64-linux-gnu.so` | `save` | library |
| 12.39% | `python` | `PyDict_Next` | dict |
| 8.17% | `_pickle.cpython-313-x86_64-linux-gnu.so` | `_Pickler_Write` | library |
| 6.25% | `_pickle.cpython-313-x86_64-linux-gnu.so` | `_Pickler_Write.constprop.3` | library |
| 4.00% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 3.37% | `python` | `PyLong_AsLongAndOverflow` | int |
| 2.26% | `_pickle.cpython-313-x86_64-linux-gnu.so` | `PyMemoTable_Set` | library |
| 1.31% | `_pickle.cpython-313-x86_64-linux-gnu.so` | `Pickler_clear` | library |
| 1.11% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 0.92% | `python` | `gc_collect_main` | gc |
| 0.87% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.72% | `_pickle.cpython-313-x86_64-linux-gnu.so` | `0x0000000000005d04` | library |
| 0.71% | `python` | `_PyObject_Malloc` | memory |
| 0.66% | `_pickle.cpython-313-x86_64-linux-gnu.so` | `0x0000000000005e94` | library |
| 0.64% | `_pickle.cpython-313-x86_64-linux-gnu.so` | `memo_put.isra.0` | library |
| 0.54% | `python` | `_PyObject_Free` | memory |
| 0.53% | `libc-2.31.so` | `pthread_attr_setschedparam` | libc |
| 0.53% | `python` | `visit_decref` | gc |

## pickle_list

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 36.79% | `_pickle.cpython-313-x86_64-linux-gnu.so` | `save` | library |
| 9.35% | `_pickle.cpython-313-x86_64-linux-gnu.so` | `_Pickler_Write` | library |
| 5.94% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 4.27% | `python` | `PyLong_AsLongAndOverflow` | int |
| 3.94% | `_pickle.cpython-313-x86_64-linux-gnu.so` | `PyMemoTable_Set` | library |
| 3.85% | `_pickle.cpython-313-x86_64-linux-gnu.so` | `_Pickler_Write.constprop.3` | library |
| 1.93% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 1.83% | `_pickle.cpython-313-x86_64-linux-gnu.so` | `Pickler_clear` | library |
| 1.44% | `python` | `_PyObject_Malloc` | memory |
| 1.34% | `python` | `gc_collect_main` | gc |
| 1.33% | `libc-2.31.so` | `pthread_attr_setschedparam` | libc |
| 1.19% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.16% | `_pickle.cpython-313-x86_64-linux-gnu.so` | `memo_put.isra.0` | library |
| 1.06% | `python` | `_PyObject_Free` | memory |
| 0.75% | `_pickle.cpython-313-x86_64-linux-gnu.so` | `0x0000000000005d04` | library |
| 0.74% | `python` | `visit_decref` | gc |
| 0.54% | `python` | `_Py_dict_lookup` | lookup |
| 0.52% | `python` | `_PyThreadState_GetCurrent` | unknown |
| 0.51% | `python` | `visit_reachable` | gc |

## pickle_pure_python

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 43.20% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 3.43% | `python` | `_PyObject_Malloc` | memory |
| 3.39% | `python` | `_Py_dict_lookup` | lookup |
| 2.84% | `python` | `_PyObject_Free` | memory |
| 2.20% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.64% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 1.63% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.32% | `python` | `gc_collect_main` | gc |
| 1.14% | `python` | `initialize_locals` | interpreter |
| 1.12% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.91% | `python` | `tupledealloc` | memory |
| 0.72% | `python` | `PyBuffer_FillInfo` | miscobj |
| 0.70% | `python` | `_PyType_Lookup` | lookup |
| 0.70% | `python` | `PyBuffer_Release` | miscobj |
| 0.69% | `python` | `visit_decref` | gc |
| 0.68% | `python` | `PyDict_GetItemRef` | dict |
| 0.60% | `python` | `dict_get` | dict |
| 0.55% | `python` | `bytes_concat` | str |
| 0.54% | `python` | `tuple_alloc` | memory |
| 0.50% | `python` | `insertdict` | dict |

## pidigits

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 31.40% | `python` | `x_divrem` | int |
| 21.58% | `python` | `k_mul` | int |
| 12.00% | `python` | `x_add` | int |
| 7.51% | `python` | `x_sub` | int |
| 5.50% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 2.30% | `libc-2.31.so` | `pthread_attr_setschedparam` | libc |
| 1.75% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 0.97% | `python` | `_PyObject_Malloc` | memory |
| 0.86% | `python` | `_PyObject_Free` | memory |
| 0.81% | `python` | `gc_collect_main` | gc |
| 0.80% | `python` | `unicodekeys_lookup_unicode` | lookup |

## pprint

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 44.54% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 3.90% | `python` | `_PyObject_Malloc` | memory |
| 3.16% | `python` | `_PyObject_Free` | memory |
| 3.06% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.97% | `python` | `tupledealloc` | memory |
| 1.93% | `python` | `_PyType_Lookup` | lookup |
| 1.91% | `python` | `_Py_type_getattro_impl` | dynamic |
| 1.65% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 1.39% | `python` | `_Py_type_getattro` | lookup |
| 1.27% | `python` | `_PyUnicode_JoinArray.part.0` | str |
| 1.06% | `python` | `long_to_decimal_string_internal` | int |
| 1.02% | `python` | `_Py_dict_lookup` | lookup |
| 1.00% | `python` | `_PyTuple_FromArraySteal` | tuple |
| 1.00% | `python` | `set_lookkey` | miscobj |
| 0.99% | `python` | `PyUnicode_Format` | str |
| 0.96% | `python` | `tuple_alloc` | memory |
| 0.82% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.62% | `python` | `resize_compact` | str |
| 0.57% | `python` | `_PyTrash_end` | gc |
| 0.54% | `python` | `_copy_characters.part.0.constprop.0` | str |
| 0.54% | `python` | `initialize_locals` | interpreter |
| 0.52% | `python` | `PyObject_IsSubclass` | dynamic |
| 0.51% | `python` | `subtype_dealloc` | memory |
| 0.51% | `python` | `_Py_NewReference` | memory |
| 0.51% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.51% | `python` | `_PyUnicodeWriter_WriteSubstring.part.0` | str |
| 0.50% | `python` | `PyObject_GetAttr` | dynamic |
| 0.50% | `python` | `list_dealloc` | memory |

## pycparser

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 35.22% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 11.22% | `python` | `sre_ucs1_match` | library |
| 4.42% | `python` | `gc_collect_main` | gc |
| 2.62% | `python` | `_PyObject_Malloc` | memory |
| 2.28% | `python` | `_PyObject_Free` | memory |
| 2.19% | `libc-2.31.so` | `pthread_attr_setschedparam` | libc |
| 2.09% | `python` | `_Py_dict_lookup` | lookup |
| 1.62% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.17% | `python` | `visit_decref` | gc |
| 1.14% | `python` | `PySlice_AdjustIndices` | miscobj |
| 1.08% | `python` | `PyDict_GetItemRef` | dict |
| 1.08% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.07% | `python` | `visit_reachable` | gc |
| 1.05% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 0.97% | `python` | `subtype_traverse` | gc |
| 0.91% | `python` | `initialize_locals` | interpreter |
| 0.86% | `python` | `_sre_SRE_Pattern_match` | library |
| 0.83% | `python` | `_PyType_Lookup` | lookup |
| 0.82% | `python` | `pattern_new_match.isra.0.part.0` | memory |
| 0.79% | `python` | `subtype_dealloc` | memory |
| 0.76% | `python` | `list_ass_slice` | list |
| 0.70% | `python` | `sre_ucs1_count` | library |
| 0.55% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.52% | `python` | `_PyEvalFramePushAndInit` | interpreter |

## pyflate

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 47.69% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 3.84% | `python` | `_PyObject_Free` | memory |
| 3.51% | `python` | `list_ass_slice` | list |
| 3.48% | `python` | `list_dealloc` | memory |
| 3.31% | `python` | `_PyObject_Malloc` | memory |
| 2.62% | `python` | `list_concat` | list |
| 2.20% | `libc-2.31.so` | `pthread_attr_setschedparam` | libc |
| 1.95% | `python` | `PyNumber_AsSsize_t` | dynamic |
| 1.60% | `python` | `list_slice.isra.0` | list |
| 1.38% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 1.11% | `python` | `_PyLong_Add` | int |
| 1.10% | `python` | `PyLong_AsSsize_t` | int |
| 1.06% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 0.99% | `python` | `_PyLong_Subtract` | int |
| 0.88% | `python` | `PySlice_AdjustIndices` | miscobj |
| 0.86% | `python` | `_PyBuildSlice_ConsumeRefs` | miscobj |
| 0.81% | `python` | `long_lshift` | int |
| 0.74% | `python` | `list_sort_impl` | list |
| 0.74% | `python` | `stringlib_bytes_join` | str |
| 0.73% | `python` | `_Py_NewReference` | memory |
| 0.72% | `python` | `bytes_subscript` | str |
| 0.67% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.55% | `python` | `PyObject_GetItem` | dynamic |
| 0.54% | `python` | `unsafe_long_compare` | unknown |
| 0.53% | `python` | `long_lshift1` | int |
| 0.50% | `python` | `long_dealloc` | memory |

## python_startup

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 7.42% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 5.19% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 4.54% | `python` | `gc_collect_main` | gc |
| 3.13% | `python` | `_PyObject_Malloc` | memory |
| 3.02% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 2.58% | `python` | `visit_decref` | gc |
| 2.25% | `python` | `_Py_dict_lookup` | lookup |
| 2.14% | `python` | `visit_reachable` | gc |
| 1.92% | `python` | `r_object` | import |
| 1.62% | `python` | `update_one_slot` | lookup |
| 1.62% | `python` | `_PyObject_Free` | memory |
| 1.45% | `python` | `type_ready` | dynamic |
| 1.41% | `python` | `find_name_in_mro` | lookup |
| 1.40% | `python` | `siphash13` | str |
| 1.19% | `python` | `_PyCode_Quicken` | interpreter |
| 1.18% | `python` | `_Py_hashtable_get_entry_generic` | unknown |
| 1.02% | `libc-2.31.so` | `pthread_attr_setschedparam` | libc |
| 0.98% | `python` | `tupledealloc` | memory |
| 0.88% | `ld-2.31.so` | `_dl_rtld_di_serinfo` | library |
| 0.86% | `python` | `_PyUnicode_FromUCS1.part.0` | str |
| 0.85% | `[kernel.kallsyms]` | `native_irq_return_iret` | kernel |
| 0.83% | `python` | `dict_traverse` | gc |
| 0.83% | `python` | `_PyType_Lookup` | lookup |
| 0.74% | `python` | `ascii_decode` | str |
| 0.70% | `python` | `_PyDict_GetItem_KnownHash` | dict |
| 0.70% | `python` | `insertdict` | dict |
| 0.67% | `python` | `intern_string_constants` | interpreter |
| 0.60% | `[kernel.kallsyms]` | `sync_regs` | kernel |
| 0.59% | `[kernel.kallsyms]` | `zap_pte_range.isra.0` | kernel |
| 0.52% | `python` | `_PyFrame_ClearExceptCode` | interpreter |

## python_startup_no_site

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 7.09% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 5.54% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 5.00% | `python` | `gc_collect_main` | gc |
| 3.09% | `python` | `_PyObject_Malloc` | memory |
| 3.05% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 2.76% | `python` | `visit_decref` | gc |
| 2.32% | `python` | `_Py_dict_lookup` | lookup |
| 2.30% | `python` | `visit_reachable` | gc |
| 1.93% | `python` | `r_object` | import |
| 1.63% | `python` | `update_one_slot` | lookup |
| 1.63% | `python` | `_PyObject_Free` | memory |
| 1.59% | `python` | `type_ready` | dynamic |
| 1.49% | `python` | `find_name_in_mro` | lookup |
| 1.40% | `python` | `siphash13` | str |
| 1.24% | `python` | `_Py_hashtable_get_entry_generic` | unknown |
| 1.24% | `python` | `_PyCode_Quicken` | interpreter |
| 1.04% | `libc-2.31.so` | `pthread_attr_setschedparam` | libc |
| 0.97% | `ld-2.31.so` | `_dl_rtld_di_serinfo` | library |
| 0.91% | `python` | `tupledealloc` | memory |
| 0.88% | `python` | `dict_traverse` | gc |
| 0.88% | `[kernel.kallsyms]` | `native_irq_return_iret` | kernel |
| 0.86% | `python` | `_PyType_Lookup` | lookup |
| 0.86% | `python` | `_PyUnicode_FromUCS1.part.0` | str |
| 0.78% | `python` | `_PyDict_GetItem_KnownHash` | dict |
| 0.72% | `python` | `insertdict` | dict |
| 0.70% | `python` | `intern_string_constants` | interpreter |
| 0.69% | `python` | `ascii_decode` | str |
| 0.66% | `[kernel.kallsyms]` | `sync_regs` | kernel |
| 0.58% | `[kernel.kallsyms]` | `zap_pte_range.isra.0` | kernel |
| 0.54% | `python` | `build_indices_unicode` | dict |
| 0.53% | `python` | `_PyUnicode_InternInPlace` | str |
| 0.51% | `[kernel.kallsyms]` | `clear_page_erms` | kernel |
| 0.50% | `libc-2.31.so` | `__gconv_get_alias_db` | libc |

## raytrace

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 54.83% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 3.24% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 2.39% | `python` | `_PyObject_Free` | memory |
| 1.90% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 1.87% | `python` | `_PyObject_Malloc` | memory |
| 1.63% | `python` | `PyFloat_FromDouble` | float |
| 1.54% | `python` | `subtype_dealloc` | memory |
| 1.36% | `python` | `float_dealloc` | memory |
| 1.12% | `python` | `PyType_IsSubtype` | dynamic |
| 0.91% | `python` | `_PyType_NewManagedObject` | memory |
| 0.91% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 0.88% | `python` | `float_sub` | float |
| 0.75% | `python` | `PyNumber_Subtract` | dynamic |
| 0.70% | `python` | `_PyObject_FreeInstanceAttributes` | dynamic |
| 0.70% | `python` | `_PyThreadState_PopFrame` | interpreter |
| 0.68% | `python` | `_Py_NewReference` | memory |
| 0.67% | `python` | `_PyType_Lookup` | lookup |
| 0.66% | `python` | `initialize_locals` | interpreter |
| 0.62% | `python` | `tupledealloc` | memory |
| 0.58% | `python` | `vectorcall_maybe.constprop.0` | unknown |
| 0.53% | `python` | `gc_collect_main` | gc |
| 0.53% | `python` | `PyLong_AsDouble` | int |
| 0.52% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.51% | `python` | `_PyFloat_ExactDealloc` | memory |
| 0.50% | `python` | `_PyEvalFramePushAndInit` | interpreter |

## regex_compile

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 44.73% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 3.22% | `python` | `sre_ucs1_match` | library |
| 3.11% | `python` | `_PyObject_Malloc` | memory |
| 2.82% | `python` | `_PyObject_Free` | memory |
| 1.78% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.41% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 1.17% | `python` | `PyNumber_AsSsize_t` | dynamic |
| 1.02% | `python` | `tupledealloc` | memory |
| 0.94% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.89% | `python` | `_PyType_Lookup` | lookup |
| 0.87% | `python` | `gc_collect_main` | gc |
| 0.67% | `python` | `bytearray_ass_subscript` | miscobj |
| 0.64% | `python` | `sre_ucs2_charset.isra.0` | library |
| 0.63% | `python` | `PyLong_FromLong` | int |
| 0.61% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.60% | `python` | `list_dealloc` | memory |
| 0.59% | `python` | `tuple_alloc` | memory |
| 0.52% | `python` | `sre_search` | library |
| 0.51% | `python` | `_Py_dict_lookup` | lookup |

## regex_dna

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 32.27% | `python` | `sre_ucs1_match` | library |
| 25.74% | `python` | `sre_ucs2_charset.isra.0` | library |
| 8.29% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 5.97% | `python` | `sre_search` | library |
| 3.28% | `libm-2.31.so` | `__fmod_finite` | library |
| 1.41% | `_bisect.cpython-313-x86_64-linux-gnu.so` | `_bisect_bisect_right` | library |
| 1.24% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 0.90% | `python` | `pattern_subx` | library |
| 0.82% | `python` | `float_rem` | float |
| 0.70% | `python` | `gc_collect_main` | gc |
| 0.70% | `python` | `_PyObject_Malloc` | memory |
| 0.64% | `python` | `float_richcompare` | float |
| 0.60% | `python` | `unicodekeys_lookup_unicode` | lookup |

## regex_effbot

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 37.39% | `python` | `sre_ucs1_match` | library |
| 13.48% | `python` | `sre_ucs2_charset.isra.0` | library |
| 6.42% | `python` | `sre_search` | library |
| 5.75% | `python` | `_PyObject_Free` | memory |
| 5.74% | `python` | `_PyObject_Malloc` | memory |
| 5.44% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 2.11% | `python` | `sre_ucs1_count` | library |
| 1.16% | `python` | `gc_collect_main` | gc |
| 1.04% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.75% | `python` | `PyObject_Malloc` | dynamic |
| 0.65% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 0.57% | `python` | `visit_decref` | gc |
| 0.54% | `python` | `_Py_dict_lookup` | lookup |

## regex_v8

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 30.81% | `python` | `sre_ucs1_match` | library |
| 11.00% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 4.44% | `python` | `sre_search` | library |
| 3.62% | `python` | `sre_ucs1_count` | library |
| 3.13% | `python` | `PyCode_Addr2Line` | exceptions |
| 2.64% | `python` | `_PyObject_Malloc` | memory |
| 2.50% | `python` | `_PyObject_Free` | memory |
| 1.89% | `libc-2.31.so` | `pthread_attr_setschedparam` | libc |
| 1.48% | `python` | `pattern_subx` | library |
| 1.39% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 1.31% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.22% | `python` | `gc_collect_main` | gc |
| 0.92% | `python` | `_sre_SRE_Pattern_search` | library |
| 0.91% | `python` | `pattern_new_match.isra.0.part.0` | memory |
| 0.86% | `python` | `_Py_dict_lookup` | lookup |
| 0.67% | `python` | `visit_decref` | gc |
| 0.53% | `libc-2.31.so` | `malloc` | libc |
| 0.51% | `python` | `_PyUnicode_ToLowercase` | str |

## richards

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 53.30% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 4.31% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 3.56% | `python` | `_PyType_Lookup` | lookup |
| 2.75% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.96% | `python` | `PyObject_GenericGetAttr` | dynamic |
| 1.83% | `python` | `_PyObject_GetMethod` | dynamic |
| 1.62% | `python` | `_PyObject_GetInstanceAttribute` | dynamic |
| 1.42% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 1.28% | `python` | `gc_collect_main` | gc |
| 1.27% | `python` | `_PyObject_Malloc` | memory |
| 1.09% | `python` | `_PyObject_Free` | memory |
| 1.06% | `python` | `PyObject_GetAttr` | dynamic |
| 1.00% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 0.68% | `python` | `visit_decref` | gc |
| 0.62% | `python` | `_Py_dict_lookup` | lookup |
| 0.58% | `python` | `initialize_locals` | interpreter |
| 0.56% | `python` | `_PyThreadState_PopFrame` | interpreter |
| 0.51% | `python` | `visit_reachable` | gc |

## richards_super

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 53.04% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 4.19% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 3.44% | `python` | `_PyType_Lookup` | lookup |
| 2.89% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.77% | `python` | `_PyObject_GetMethod` | dynamic |
| 1.76% | `python` | `PyObject_GenericGetAttr` | dynamic |
| 1.47% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 1.46% | `python` | `_PyObject_GetInstanceAttribute` | dynamic |
| 1.19% | `python` | `PyObject_GetAttr` | dynamic |
| 1.15% | `python` | `gc_collect_main` | gc |
| 1.15% | `python` | `_PyObject_Malloc` | memory |
| 0.99% | `python` | `_PyObject_Free` | memory |
| 0.89% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 0.81% | `python` | `_Py_dict_lookup` | lookup |
| 0.68% | `python` | `PyDict_GetItemRef` | dict |
| 0.61% | `python` | `visit_decref` | gc |
| 0.60% | `python` | `_PyObject_StoreInstanceAttribute` | dynamic |
| 0.56% | `python` | `do_super_lookup` | dynamic |
| 0.54% | `python` | `_PyObject_GenericSetAttrWithDict` | dynamic |
| 0.54% | `python` | `_PyThreadState_PopFrame` | interpreter |
| 0.50% | `python` | `initialize_locals` | interpreter |

## scimark

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 44.15% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 3.93% | `python` | `PyNumber_AsSsize_t` | dynamic |
| 3.46% | `python` | `_PyObject_Malloc` | memory |
| 3.39% | `python` | `_PyObject_Free` | memory |
| 3.38% | `python` | `PyFloat_FromDouble` | float |
| 2.66% | `array.cpython-313-x86_64-linux-gnu.so` | `array_subscr` | library |
| 2.32% | `python` | `PyType_GetModuleByDef` | dynamic |
| 2.21% | `python` | `vgetargs1_impl` | calls |
| 1.88% | `python` | `PyObject_GetItem` | dynamic |
| 1.65% | `python` | `_PyLong_Add` | int |
| 1.63% | `python` | `convertitem.constprop.0` | unknown |
| 1.39% | `python` | `PyLong_AsSsize_t` | int |
| 1.21% | `python` | `float_dealloc` | memory |
| 1.17% | `array.cpython-313-x86_64-linux-gnu.so` | `array_ass_subscr` | library |
| 0.93% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 0.89% | `python` | `_PyFloat_ExactDealloc` | memory |
| 0.87% | `python` | `_Py_NewReference` | memory |
| 0.76% | `array.cpython-313-x86_64-linux-gnu.so` | `d_setitem` | library |
| 0.76% | `python` | `_PyLong_Multiply` | int |
| 0.76% | `python` | `PyObject_SetItem` | dynamic |
| 0.74% | `python` | `PyLong_FromLong` | int |
| 0.73% | `python` | `PyArg_Parse` | calls |
| 0.69% | `python` | `PyIndex_Check` | unknown |
| 0.68% | `array.cpython-313-x86_64-linux-gnu.so` | `d_getitem` | library |
| 0.66% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.63% | `python` | `long_dealloc` | memory |

## spectral_norm

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 42.20% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 5.98% | `python` | `_PyObject_Free` | memory |
| 5.90% | `python` | `_PyLong_Add` | int |
| 5.85% | `python` | `_PyObject_Malloc` | memory |
| 2.84% | `python` | `float_div` | float |
| 2.24% | `python` | `long_div` | int |
| 1.76% | `python` | `_PyLong_Multiply` | int |
| 1.65% | `python` | `PyNumber_TrueDivide` | dynamic |
| 1.64% | `python` | `PyType_IsSubtype` | dynamic |
| 1.38% | `python` | `enum_next` | miscobj |
| 1.26% | `python` | `listiter_next` | list |
| 1.16% | `python` | `PyLong_AsDouble` | int |
| 1.08% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.02% | `python` | `float_mul` | float |
| 1.00% | `python` | `PyLong_FromLong` | int |
| 0.95% | `python` | `gc_collect_main` | gc |
| 0.95% | `python` | `_Py_NewReference` | memory |
| 0.88% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.76% | `python` | `float_dealloc` | memory |
| 0.73% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.69% | `python` | `long_dealloc` | memory |
| 0.62% | `python` | `PyNumber_FloorDivide` | dynamic |
| 0.57% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 0.53% | `python` | `visit_decref` | gc |

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
| 41.95% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 3.04% | `python` | `_PyObject_Malloc` | memory |
| 2.95% | `python` | `_PyObject_Free` | memory |
| 2.48% | `python` | `_PyType_Lookup` | lookup |
| 2.03% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.86% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.39% | `python` | `gc_collect_main` | gc |
| 1.37% | `python` | `PyType_IsSubtype` | dynamic |
| 1.26% | `python` | `_Py_dict_lookup` | lookup |
| 1.25% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 1.24% | `python` | `tupledealloc` | memory |
| 1.09% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.83% | `python` | `dictiter_iternextitem` | dict |
| 0.80% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.75% | `python` | `initialize_locals` | interpreter |
| 0.68% | `python` | `_PyObject_GC_New` | gc |
| 0.67% | `python` | `visit_decref` | gc |
| 0.64% | `python` | `PyObject_GC_Del` | gc |
| 0.55% | `python` | `tuple_alloc` | memory |
| 0.51% | `python` | `PyObject_GetAttr` | dynamic |
| 0.50% | `python` | `PyObject_IsInstance` | dynamic |
| 0.50% | `python` | `PyObject_GetOptionalAttr` | dynamic |

## sqlite_synth

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 11.41% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 8.83% | `libpthread-2.31.so` | `pthread_mutex_unlock` | library |
| 8.74% | `libpthread-2.31.so` | `__pthread_mutex_lock` | library |
| 3.95% | `libsqlite3.so.0.8.6` | `sqlite3_reset` | library |
| 2.96% | `python` | `_PyObject_Malloc` | memory |
| 2.89% | `python` | `_PyObject_Free` | memory |
| 1.93% | `python` | `take_gil` | gil |
| 1.86% | `libm-2.31.so` | `f64xsubf128` | library |
| 1.46% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.27% | `python` | `gc_collect_main` | gc |
| 1.10% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 1.08% | `libsqlite3.so.0.8.6` | `sqlite3_randomness` | library |
| 1.06% | `python` | `tupledealloc` | memory |
| 0.88% | `_sqlite3.cpython-313-x86_64-linux-gnu.so` | `_pysqlite_query_execute` | library |
| 0.86% | `libpthread-2.31.so` | `pthread_cond_signal@@GLIBC_2.3.2` | library |
| 0.79% | `libsqlite3.so.0.8.6` | `sqlite3_value_double` | library |
| 0.75% | `libc-2.31.so` | `pthread_attr_setschedparam` | libc |
| 0.72% | `libsqlite3.so.0.8.6` | `sqlite3_preupdate_old` | library |
| 0.71% | `python` | `visit_decref` | gc |
| 0.66% | `python` | `drop_gil` | gil |
| 0.64% | `python` | `_Py_dict_lookup` | lookup |
| 0.62% | `libsqlite3.so.0.8.6` | `sqlite3_value_int64` | library |
| 0.61% | `libsqlite3.so.0.8.6` | `sqlite3_extended_errcode` | library |
| 0.55% | `python` | `PyThread_get_thread_ident` | unknown |
| 0.53% | `python` | `long_to_decimal_string_internal` | int |
| 0.53% | `python` | `visit_reachable` | gc |
| 0.52% | `python` | `_Py_NewReference` | memory |
| 0.51% | `python` | `_PyThreadState_MustExit` | unknown |
| 0.50% | `python` | `list_dealloc` | memory |

## sympy

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 29.18% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 3.28% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 2.76% | `python` | `_PyObject_Malloc` | memory |
| 2.50% | `python` | `_PyType_Lookup` | lookup |
| 2.29% | `python` | `_PyObject_Free` | memory |
| 1.95% | `python` | `tupledealloc` | memory |
| 1.91% | `python` | `_Py_dict_lookup` | lookup |
| 1.85% | `python` | `gc_collect_main` | gc |
| 1.73% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 1.56% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.32% | `python` | `initialize_locals` | interpreter |
| 1.13% | `python` | `PyObject_RichCompareBool` | dynamic |
| 0.90% | `python` | `PyType_IsSubtype` | dynamic |
| 0.88% | `python` | `visit_decref` | gc |
| 0.87% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.72% | `python` | `tuple_alloc` | memory |
| 0.65% | `python` | `PyObject_GetAttr` | dynamic |
| 0.65% | `python` | `_Py_type_getattro` | lookup |
| 0.62% | `python` | `insertdict` | dict |
| 0.61% | `python` | `PyDict_GetItemRef` | dict |
| 0.61% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.60% | `python` | `visit_reachable` | gc |
| 0.56% | `python` | `PyObject_GenericGetAttr` | dynamic |
| 0.54% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.54% | `python` | `_PyObject_GC_New` | gc |
| 0.53% | `python` | `PyObject_GC_Del` | gc |
| 0.52% | `python` | `_PyTrash_end` | gc |

## telco

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 16.51% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 4.60% | `python` | `_PyObject_Free` | memory |
| 4.51% | `python` | `_PyObject_Malloc` | memory |
| 4.40% | `python` | `PyType_GetModuleByDef` | dynamic |
| 1.94% | `python` | `PyContextVar_Get` | unknown |
| 1.87% | `_decimal.cpython-313-x86_64-linux-gnu.so` | `nm_mpd_qadd` | library |
| 1.86% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 1.71% | `python` | `tupledealloc` | memory |
| 1.65% | `_decimal.cpython-313-x86_64-linux-gnu.so` | `_mpd_qaddsub` | library |
| 1.65% | `python` | `PyObject_GC_Del` | gc |
| 1.56% | `python` | `_PyObject_GC_New` | gc |
| 1.44% | `_decimal.cpython-313-x86_64-linux-gnu.so` | `_mpd_qmul` | library |
| 1.34% | `_decimal.cpython-313-x86_64-linux-gnu.so` | `mpd_setdigits` | library |
| 1.30% | `_decimal.cpython-313-x86_64-linux-gnu.so` | `_mpd_check_exp` | library |
| 1.25% | `python` | `PyObject_GenericGetAttr` | dynamic |
| 1.18% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.17% | `_decimal.cpython-313-x86_64-linux-gnu.so` | `nm_mpd_qmul` | library |
| 1.06% | `python` | `_PyType_Lookup` | lookup |
| 1.06% | `python` | `vgetargskeywords.constprop.0` | calls |
| 1.05% | `python` | `_PyArg_UnpackKeywordsWithVararg` | calls |
| 1.02% | `_decimal.cpython-313-x86_64-linux-gnu.so` | `_mpd_baseshiftr` | library |
| 1.00% | `python` | `gc_collect_main` | gc |
| 0.89% | `_decimal.cpython-313-x86_64-linux-gnu.so` | `mpd_qquantize` | library |
| 0.88% | `python` | `convertitem.constprop.0` | unknown |
| 0.86% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.80% | `_decimal.cpython-313-x86_64-linux-gnu.so` | `PyDecType_New` | library |
| 0.77% | `_decimal.cpython-313-x86_64-linux-gnu.so` | `dec_addstatus` | library |
| 0.70% | `_decimal.cpython-313-x86_64-linux-gnu.so` | `dec_dealloc` | library |
| 0.68% | `python` | `PyUnicode_AsUCS4` | str |
| 0.66% | `_decimal.cpython-313-x86_64-linux-gnu.so` | `dec_mpd_qquantize` | library |
| 0.63% | `python` | `_Py_NewReference` | memory |
| 0.62% | `python` | `meth_dealloc` | memory |
| 0.62% | `python` | `vgetargs1_impl` | calls |
| 0.61% | `python` | `PyCMethod_New` | memory |
| 0.61% | `python` | `_Py_dict_lookup` | lookup |
| 0.60% | `_decimal.cpython-313-x86_64-linux-gnu.so` | `mpd_qshiftr` | library |
| 0.57% | `python` | `PyDict_GetItemRef` | dict |
| 0.55% | `python` | `_PyTuple_FromArray` | tuple |
| 0.54% | `python` | `tuple_alloc` | memory |
| 0.54% | `_decimal.cpython-313-x86_64-linux-gnu.so` | `mpd_qfinalize.part.0` | library |
| 0.51% | `python` | `visit_decref` | gc |
| 0.51% | `python` | `_PyObject_GC_Link` | gc |

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
| 50.76% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 4.50% | `python` | `_PyObject_Malloc` | memory |
| 4.34% | `python` | `set_lookkey` | miscobj |
| 3.77% | `python` | `_PyObject_Free` | memory |
| 2.45% | `python` | `_PyLong_Add` | int |
| 2.40% | `python` | `_PyUnicode_Equal` | str |
| 2.20% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.94% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 1.40% | `python` | `PySequence_Contains` | dynamic |
| 1.36% | `python` | `set_contains` | miscobj |
| 1.21% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.18% | `python` | `_Py_dict_lookup` | lookup |
| 1.17% | `python` | `PyDict_GetItemRef` | dict |
| 0.80% | `python` | `tupledealloc` | memory |
| 0.65% | `python` | `_PyIncrementalNewlineDecoder_decode` | memory |
| 0.63% | `python` | `long_dealloc` | memory |
| 0.62% | `python` | `replace` | str |
| 0.53% | `python` | `_PyUnicode_FromUCS4.part.0` | str |
| 0.52% | `python` | `_Py_NewReference` | memory |
| 0.51% | `python` | `PyNumber_AsSsize_t` | dynamic |
| 0.51% | `python` | `tuple_alloc` | memory |

## tornado_http

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 27.81% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 3.47% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 2.63% | `python` | `_PyObject_Malloc` | memory |
| 2.52% | `python` | `gc_collect_main` | gc |
| 2.21% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.87% | `python` | `_PyObject_Free` | memory |
| 1.61% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.28% | `python` | `visit_decref` | gc |
| 1.14% | `python` | `tupledealloc` | memory |
| 1.13% | `python` | `_PyType_Lookup` | lookup |
| 1.11% | `python` | `visit_reachable` | gc |
| 1.10% | `python` | `_Py_dict_lookup` | lookup |
| 0.82% | `python` | `initialize_locals` | interpreter |
| 0.77% | `libc-2.31.so` | `pthread_attr_setschedparam` | libc |
| 0.60% | `[kernel.kallsyms]` | `copy_user_enhanced_fast_string` | kernel |
| 0.55% | `python` | `PyObject_GC_UnTrack` | gc |

## typing_runtime_protocols

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 32.05% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 2.98% | `python` | `_Py_dict_lookup` | lookup |
| 2.85% | `python` | `_PyObject_Malloc` | memory |
| 2.73% | `python` | `_PyObject_Free` | memory |
| 2.30% | `python` | `tupledealloc` | memory |
| 2.26% | `python` | `_PyType_Lookup` | lookup |
| 2.22% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.76% | `python` | `_PyObject_MakeTpCall` | dynamic |
| 1.44% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.43% | `python` | `_PyTuple_FromArray` | tuple |
| 1.42% | `python` | `_Py_type_getattro` | lookup |
| 1.35% | `python` | `PyObject_RichCompareBool` | dynamic |
| 1.32% | `python` | `tuple_alloc` | memory |
| 1.16% | `python` | `gc_collect_main` | gc |
| 1.06% | `python` | `bounded_lru_cache_wrapper` | unknown |
| 1.06% | `python` | `tuplehash` | tuple |
| 1.02% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 0.87% | `python` | `_PyObject_GC_New` | gc |
| 0.77% | `python` | `PyObject_Vectorcall` | dynamic |
| 0.77% | `python` | `_PyTrash_end` | gc |
| 0.76% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.71% | `python` | `frame_dealloc` | memory |
| 0.69% | `python` | `PyObject_Hash` | dynamic |
| 0.67% | `python` | `PyObject_GenericGetAttr` | dynamic |
| 0.66% | `python` | `PyObject_GC_Del` | gc |
| 0.64% | `python` | `set_lookkey` | miscobj |
| 0.58% | `python` | `getset_get` | dynamic |
| 0.58% | `python` | `visit_decref` | gc |
| 0.56% | `python` | `_PyDict_GetItem_KnownHash` | dict |
| 0.56% | `python` | `_Py_NewReference` | memory |
| 0.56% | `python` | `_PyTrash_begin` | gc |
| 0.54% | `python` | `PyObject_GetAttr` | dynamic |
| 0.54% | `python` | `wrap_descr_get` | unknown |
| 0.54% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.51% | `python` | `PyArg_UnpackTuple` | calls |

## unpack_sequence

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 76.20% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 1.13% | `python` | `gc_collect_main` | gc |
| 1.03% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.94% | `python` | `_PyObject_Malloc` | memory |
| 0.71% | `python` | `_PyObject_Free` | memory |
| 0.61% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 0.58% | `python` | `visit_decref` | gc |

## unpickle

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 7.54% | `_pickle.cpython-313-x86_64-linux-gnu.so` | `load` | library |
| 7.07% | `python` | `_PyObject_Malloc` | memory |
| 5.89% | `python` | `_PyObject_Free` | memory |
| 5.12% | `python` | `siphash13` | str |
| 4.61% | `_pickle.cpython-313-x86_64-linux-gnu.so` | `load_counted_binunicode` | library |
| 4.51% | `python` | `insertdict` | dict |
| 4.43% | `python` | `ascii_decode` | str |
| 4.10% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 4.10% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 3.63% | `python` | `unicode_decode_utf8` | str |
| 2.85% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 2.56% | `python` | `PyUnicode_New.part.0` | memory |
| 2.54% | `_pickle.cpython-313-x86_64-linux-gnu.so` | `do_setitems.isra.0` | library |
| 2.21% | `python` | `_Py_dict_lookup` | lookup |
| 1.88% | `python` | `dict_ass_sub` | dict |
| 1.83% | `_pickle.cpython-313-x86_64-linux-gnu.so` | `_Unpickler_MemoPut` | library |
| 1.31% | `python` | `free_keys_object` | dict |
| 1.26% | `python` | `build_indices_unicode` | dict |
| 1.18% | `python` | `find_empty_slot` | dict |
| 1.10% | `python` | `_PyObject_Realloc` | memory |
| 1.07% | `python` | `PyObject_SetItem` | dynamic |
| 1.04% | `_pickle.cpython-313-x86_64-linux-gnu.so` | `Unpickler_clear` | library |
| 0.92% | `python` | `unicode_dealloc` | memory |
| 0.87% | `python` | `gc_collect_main` | gc |
| 0.74% | `python` | `PyObject_IS_GC` | gc |
| 0.69% | `_pickle.cpython-313-x86_64-linux-gnu.so` | `Pdata_push` | library |
| 0.64% | `python` | `_Py_NewReference` | memory |
| 0.63% | `python` | `list_dealloc` | memory |

## unpickle_list

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 14.75% | `_pickle.cpython-313-x86_64-linux-gnu.so` | `load` | library |
| 7.00% | `python` | `list_dealloc` | memory |
| 5.85% | `python` | `PyList_New` | memory |
| 5.78% | `python` | `list_ass_slice` | list |
| 5.68% | `python` | `_PyObject_Free` | memory |
| 4.29% | `python` | `_PyObject_Malloc` | memory |
| 4.11% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 4.00% | `_pickle.cpython-313-x86_64-linux-gnu.so` | `do_append.isra.0` | library |
| 3.92% | `_pickle.cpython-313-x86_64-linux-gnu.so` | `Pdata_push` | library |
| 3.47% | `python` | `PyLong_FromLong` | int |
| 2.15% | `python` | `_PyObject_Calloc` | memory |
| 2.08% | `python` | `PyMem_Calloc` | memory |
| 1.66% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 1.56% | `python` | `_Py_NewReference` | memory |
| 1.39% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 1.20% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 1.15% | `python` | `_PyObject_Realloc` | memory |
| 1.09% | `python` | `_PyTrash_end` | gc |
| 1.06% | `python` | `gc_collect_main` | gc |
| 1.06% | `python` | `PyObject_GC_UnTrack` | gc |
| 1.01% | `_pickle.cpython-313-x86_64-linux-gnu.so` | `marker.isra.0` | library |
| 1.01% | `python` | `_Py_Dealloc` | memory |
| 0.95% | `python` | `_PyTrash_begin` | gc |
| 0.71% | `_pickle.cpython-313-x86_64-linux-gnu.so` | `_Unpickler_MemoPut` | library |
| 0.64% | `_pickle.cpython-313-x86_64-linux-gnu.so` | `0x0000000000005be4` | library |
| 0.57% | `python` | `visit_decref` | gc |
| 0.50% | `python` | `_PyTrash_cond` | gc |

## unpickle_pure_python

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 50.05% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 2.26% | `python` | `_Py_dict_lookup` | lookup |
| 2.15% | `python` | `_PyObject_Malloc` | memory |
| 2.08% | `python` | `PyObject_IsTrue` | dynamic |
| 1.79% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 1.59% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 1.57% | `python` | `_PyObject_Free` | memory |
| 1.47% | `python` | `PyDict_GetItemRef` | dict |
| 1.24% | `python` | `PyNumber_AsSsize_t` | dynamic |
| 1.13% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.99% | `python` | `_PyEval_FrameClearAndPop` | interpreter |
| 0.96% | `python` | `insertdict` | dict |
| 0.92% | `python` | `gc_collect_main` | gc |
| 0.83% | `python` | `initialize_locals` | interpreter |
| 0.81% | `python` | `tupledealloc` | memory |
| 0.77% | `python` | `list_subscript` | list |
| 0.74% | `python` | `_io_BytesIO_read` | unknown |
| 0.71% | `python` | `bytes_subscript` | str |
| 0.70% | `python` | `PyObject_GetItem` | dynamic |
| 0.69% | `python` | `unicode_decode_utf8` | str |
| 0.63% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.62% | `python` | `PyLong_AsSsize_t` | int |
| 0.61% | `python` | `PyUnicode_Decode.part.0` | str |
| 0.58% | `python` | `PyBytes_FromStringAndSize` | str |

## xml_etree

| percentage | object | symbol | category |
| ---: | :--- | :--- | :--- |
| 21.35% | `python` | `_PyEval_EvalFrameDefault` | interpreter |
| 4.00% | `python` | `_PyObject_Malloc` | memory |
| 2.93% | `python` | `_PyObject_Free` | memory |
| 2.74% | `python` | `gc_collect_main` | gc |
| 2.28% | `pyexpat.cpython-313-x86_64-linux-gnu.so` | `normal_updatePosition` | library |
| 2.00% | `python` | `_PyType_Lookup` | lookup |
| 1.96% | `pyexpat.cpython-313-x86_64-linux-gnu.so` | `normal_contentTok` | library |
| 1.82% | `libc-2.31.so` | `__nss_database_lookup` | libc |
| 1.68% | `python` | `visit_decref` | gc |
| 1.61% | `python` | `visit_reachable` | gc |
| 1.59% | `python` | `PyObject_GenericGetAttr` | dynamic |
| 1.58% | `python` | `_io_TextIOWrapper_write` | unknown |
| 1.46% | `python` | `_Py_dict_lookup` | lookup |
| 1.32% | `pyexpat.cpython-313-x86_64-linux-gnu.so` | `sip24_update` | library |
| 1.09% | `pyexpat.cpython-313-x86_64-linux-gnu.so` | `accountingDiffTolerated.part.0` | library |
| 1.02% | `pyexpat.cpython-313-x86_64-linux-gnu.so` | `normal_nameLength` | library |
| 0.97% | `_elementtree.cpython-313-x86_64-linux-gnu.so` | `expat_end_handler` | library |
| 0.96% | `python` | `initialize_locals` | interpreter |
| 0.95% | `pyexpat.cpython-313-x86_64-linux-gnu.so` | `doContent` | library |
| 0.95% | `pyexpat.cpython-313-x86_64-linux-gnu.so` | `lookup.constprop.0` | library |
| 0.92% | `python` | `unicodekeys_lookup_unicode` | lookup |
| 0.86% | `_elementtree.cpython-313-x86_64-linux-gnu.so` | `treebuilder_handle_start` | library |
| 0.83% | `python` | `_PyFrame_ClearExceptCode` | interpreter |
| 0.82% | `python` | `tupledealloc` | memory |
| 0.76% | `_elementtree.cpython-313-x86_64-linux-gnu.so` | `element_gc_traverse` | library |
| 0.73% | `python` | `PyUnicode_Contains` | str |
| 0.68% | `python` | `siphash13` | str |
| 0.67% | `python` | `PyObject_GetAttr` | dynamic |
| 0.62% | `_elementtree.cpython-313-x86_64-linux-gnu.so` | `elementiter_next` | library |
| 0.61% | `python` | `ascii_decode` | str |
| 0.59% | `python` | `_PyEvalFramePushAndInit` | interpreter |
| 0.58% | `python` | `_PyObject_GenericGetAttrWithDict` | dynamic |
| 0.57% | `python` | `_PyObject_GetMethod` | dynamic |
| 0.57% | `python` | `PyUnicode_New.part.0` | memory |
| 0.57% | `python` | `_copy_characters.part.0.constprop.0` | str |
| 0.56% | `pyexpat.cpython-313-x86_64-linux-gnu.so` | `normal_getAtts` | library |
| 0.56% | `python` | `PyObject_GC_UnTrack` | gc |
| 0.55% | `python` | `list_dealloc` | memory |
| 0.54% | `python` | `getset_get` | dynamic |
| 0.54% | `python` | `_Py_NewReference` | memory |
| 0.54% | `pyexpat.cpython-313-x86_64-linux-gnu.so` | `sip24_final` | library |


## Categories

### interpreter

32.46% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 28.85% | python | _PyEval_EvalFrameDefault |
| 1.15% | python | _PyFrame_ClearExceptCode |
| 0.60% | python | initialize_locals |
| 0.44% | python | _PyEval_FrameClearAndPop |
| 0.29% | python | _PyEvalFramePushAndInit |
| 0.20% | python | _PyCode_Quicken |
| 0.18% | python | _PyThreadState_PopFrame |
| 0.14% | python | _PyEval_Vector |
| 0.11% | python | intern_string_constants |
| 0.08% | python | _PyPegen_is_memoized |
| 0.07% | python | _PyEval_SliceIndex |
| 0.07% | python | _PyFrame_Traverse |
| 0.06% | python | _Py_GetBaseOpcode |
| 0.04% | python | advance |
| 0.04% | python | _PyPegen_expect_token |
| 0.03% | python | _PyPegen_update_memo |
| 0.02% | python | _PyPegen_fill_token |
| 0.02% | python | _PyCode_Validate |
| 0.01% | python | _PyEval_BuiltinsFromGlobals |
| 0.01% | python | _PyPegen_insert_memo |
| 0.01% | python | PyEval_SaveThread |
| 0.01% | python | _PyPegen_name_token |
| 0.01% | python | _PyFrame_New_NoTrack |

### memory

11.01% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 2.77% | python | _PyObject_Malloc |
| 2.39% | python | _PyObject_Free |
| 0.71% | python | tupledealloc |
| 0.47% | python | list_dealloc |
| 0.42% | python | _Py_NewReference |
| 0.30% | python | tuple_alloc |
| 0.25% | python | subtype_dealloc |
| 0.24% | python | _Py_Dealloc |
| 0.22% | python | PyUnicode_New.part.0 |
| 0.20% | python | PyType_GenericAlloc |
| 0.19% | python | _PyObject_Realloc |
| 0.16% | python | dict_dealloc |
| 0.14% | python | PyList_New |
| 0.13% | python | gen_dealloc |
| 0.13% | python | unicode_dealloc |
| 0.12% | python | code_dealloc |
| 0.12% | python | _PyLong_New |
| 0.11% | python | float_dealloc |
| 0.11% | python | long_dealloc |
| 0.10% | python | _PyObject_Calloc |
| 0.09% | python | PyTuple_New |
| 0.08% | python | PyFunction_NewWithQualName |
| 0.08% | python | set_dealloc |
| 0.07% | python | PyCMethod_New |
| 0.07% | python | meth_dealloc |
| 0.06% | python | slice_dealloc |
| 0.06% | python | func_dealloc |
| 0.06% | python | PyMem_Calloc |
| 0.06% | python | frame_dealloc |
| 0.06% | python | _PyCode_New |
| 0.05% | python | allocate_from_new_pool |
| 0.05% | python | pattern_new_match.isra.0.part.0 |
| 0.05% | python | PyObject_CallFinalizerFromDealloc |
| 0.05% | python | PyDict_New |
| 0.05% | python | PyUnicode_New |
| 0.04% | python | object_new |
| 0.04% | python | method_dealloc |
| 0.04% | python | PyMethod_New |
| 0.04% | python | _PyFloat_ExactDealloc |
| 0.03% | python | _PyObject_Malloc (inlined) |
| 0.03% | python | _PyType_NewManagedObject |
| 0.03% | python | PySlice_New |
| 0.03% | python | PyMem_Free |
| 0.03% | python | context_tp_dealloc |
| 0.03% | python | listiter_dealloc |
| 0.02% | python | type_new |
| 0.02% | python | object_dealloc |
| 0.02% | python | StopIteration_dealloc |
| 0.02% | python | tb_dealloc |
| 0.02% | python | BaseException_new |
| 0.02% | python | async_gen_wrapped_val_dealloc |
| 0.02% | python | PyMem_Malloc |
| 0.02% | python | tp_new_wrapper |
| 0.02% | python | async_gen_asend_dealloc |
| 0.02% | python | _PyAsyncGenValueWrapperNew |
| 0.02% | python | _PyObject_New |
| 0.01% | python | PyMem_Realloc |
| 0.01% | python | _PyIncrementalNewlineDecoder_decode |
| 0.01% | python | tupleiter_dealloc |
| 0.01% | python | cell_dealloc |
| 0.01% | python | weakref___new__ |
| 0.01% | python | structseq_dealloc |
| 0.01% | python | PyWeakref_NewRef |
| 0.01% | python | range_dealloc |
| 0.01% | python | BaseException_dealloc |
| 0.01% | python | PyCell_New |
| 0.01% | python | unicode_new |
| 0.01% | python | dictiter_dealloc |
| 0.01% | python | reversed_new_impl |
| 0.01% | python | type_dealloc |
| 0.01% | python | PyList_New.constprop.0 |

### gc

10.94% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 4.22% | python | gc_collect_main |
| 1.69% | python | visit_decref |
| 1.67% | python | visit_reachable |
| 0.35% | python | PyObject_GC_UnTrack |
| 0.31% | python | PyObject_GC_Del |
| 0.27% | python | subtype_traverse |
| 0.26% | python | list_traverse |
| 0.25% | python | _PyTrash_end |
| 0.25% | python | dict_traverse |
| 0.24% | python | _PyObject_GC_New |
| 0.21% | python | _PyTrash_begin |
| 0.20% | python | PyObject_IS_GC |
| 0.16% | python | _PyObject_GC_Link |
| 0.14% | python | _PyObject_GC_NewVar |
| 0.13% | python | set_traverse |
| 0.10% | python | func_traverse |
| 0.07% | python | _PyTrash_cond |
| 0.07% | python | type_is_gc |
| 0.06% | python | _PyDict_MaybeUntrack |
| 0.05% | python | type_traverse |
| 0.05% | python | _PyTuple_MaybeUntrack |
| 0.05% | python | gen_traverse |
| 0.03% | python | meth_traverse |
| 0.03% | python | PyObject_GC_Track |
| 0.02% | python | context_tp_traverse |
| 0.02% | python | gc_traverse |
| 0.01% | python | descr_traverse |
| 0.01% | python | module_traverse |
| 0.01% | python | _PyObject_VisitManagedDict |
| 0.01% | python | method_traverse |

### library

9.50% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 1.57% | python | sre_ucs1_match |
| 1.21% | _pickle.cpython-313-x86_64-linux-gnu.so | save |
| 0.77% | libz.so.1.2.11 | crc32_combine64 |
| 0.61% | python | sre_ucs2_charset.isra.0 |
| 0.32% | _pickle.cpython-313-x86_64-linux-gnu.so | _Pickler_Write |
| 0.31% | _json.cpython-313-x86_64-linux-gnu.so | scanstring_unicode |
| 0.28% | libz.so.1.2.11 | inflateBackEnd |
| 0.27% | _pickle.cpython-313-x86_64-linux-gnu.so | load |
| 0.23% | python | sre_search |
| 0.18% | libpthread-2.31.so | __pthread_mutex_lock |
| 0.17% | _json.cpython-313-x86_64-linux-gnu.so | scan_once_unicode |
| 0.17% | _pickle.cpython-313-x86_64-linux-gnu.so | PyMemoTable_Set |
| 0.17% | libpthread-2.31.so | pthread_mutex_unlock |
| 0.15% | _pickle.cpython-313-x86_64-linux-gnu.so | _Pickler_Write.constprop.3 |
| 0.13% | python | sre_ucs1_count |
| 0.10% | libm-2.31.so | f64xsubf128 |
| 0.10% | ld-2.31.so | _dl_rtld_di_serinfo |
| 0.08% | _pickle.cpython-313-x86_64-linux-gnu.so | Pickler_clear |
| 0.08% | _json.cpython-313-x86_64-linux-gnu.so | py_encode_basestring_ascii |
| 0.07% | tracer.cpython-313-x86_64-linux-gnu.so | CTracer_trace |
| 0.06% | libpython3.11.so.1.0 | _PyEval_EvalFrameDefault |
| 0.06% | _pickle.cpython-313-x86_64-linux-gnu.so | memo_put.isra.0 |
| 0.06% | libsqlite3.so.0.8.6 | sqlite3_reset |
| 0.06% | _pickle.cpython-313-x86_64-linux-gnu.so | load_counted_binunicode |
| 0.06% | _pickle.cpython-313-x86_64-linux-gnu.so | Pdata_push |
| 0.05% | _pickle.cpython-313-x86_64-linux-gnu.so | do_append.isra.0 |
| 0.05% | _asyncio.cpython-313-x86_64-linux-gnu.so | TaskObj_traverse |
| 0.05% | libmagic.so.1.0.0 | 0x000000000000f936 |
| 0.04% | python | _sre_SRE_Pattern_match |
| 0.04% | python | pattern_subx |
| 0.04% | libm-2.31.so | __fmod_finite |
| 0.04% | libz.so.1.2.11 | inflateCodesUsed |
| 0.03% | array.cpython-313-x86_64-linux-gnu.so | array_subscr |
| 0.03% | ld-2.31.so | _dl_catch_error |
| 0.03% | _pickle.cpython-313-x86_64-linux-gnu.so | _Unpickler_MemoPut |
| 0.03% | _pickle.cpython-313-x86_64-linux-gnu.so | do_setitems.isra.0 |
| 0.03% | _json.cpython-313-x86_64-linux-gnu.so | encoder_listencode_obj |
| 0.03% | libmagic.so.1.0.0 | 0x000000000000f932 |
| 0.03% | pyexpat.cpython-313-x86_64-linux-gnu.so | normal_updatePosition |
| 0.03% | python | _sre_SRE_Pattern_search |
| 0.02% | pyexpat.cpython-313-x86_64-linux-gnu.so | normal_contentTok |
| 0.02% | _decimal.cpython-313-x86_64-linux-gnu.so | nm_mpd_qadd |
| 0.02% | math.cpython-313-x86_64-linux-gnu.so | factorial_partial_product |
| 0.02% | libpthread-2.31.so | pthread_cond_signal@@GLIBC_2.3.2 |
| 0.02% | fastbinary.cpython-312-x86_64-linux-gnu.so | apache::thrift::py::ProtocolBase<apache::thrift::py::BinaryProtocol>::encodeValue |
| 0.02% | _pickle.cpython-313-x86_64-linux-gnu.so | memo_get.isra.0 |
| 0.02% | _decimal.cpython-313-x86_64-linux-gnu.so | _mpd_qaddsub |
| 0.02% | _pickle.cpython-313-x86_64-linux-gnu.so | 0x0000000000005d04 |
| 0.02% | _json.cpython-313-x86_64-linux-gnu.so | encoder_encode_key_value |
| 0.02% | libsqlite3.so.0.8.6 | sqlite3_randomness |
| 0.02% | _pickle.cpython-313-x86_64-linux-gnu.so | Unpickler_clear |
| 0.02% | _decimal.cpython-313-x86_64-linux-gnu.so | _mpd_qmul |
| 0.02% | _bisect.cpython-313-x86_64-linux-gnu.so | _bisect_bisect_right |
| 0.02% | libpthread-2.31.so | __errno_location |
| 0.02% | libz.so.1.2.11 | inflate |
| 0.02% | _asyncio.cpython-313-x86_64-linux-gnu.so | task_step_impl |
| 0.02% | _decimal.cpython-313-x86_64-linux-gnu.so | mpd_setdigits |
| 0.02% | pyexpat.cpython-313-x86_64-linux-gnu.so | sip24_update |
| 0.02% | _decimal.cpython-313-x86_64-linux-gnu.so | _mpd_check_exp |
| 0.02% | array.cpython-313-x86_64-linux-gnu.so | array_ass_subscr |
| 0.01% | libpython3.11.so.1.0 | _PyDict_GetItem_KnownHash |
| 0.01% | _decimal.cpython-313-x86_64-linux-gnu.so | nm_mpd_qmul |
| 0.01% | libsqlite3.so.0.8.6 | sqlite3_exec |
| 0.01% | _asyncio.cpython-313-x86_64-linux-gnu.so | TaskObj_clear |
| 0.01% | _pickle.cpython-313-x86_64-linux-gnu.so | marker.isra.0 |
| 0.01% | pyexpat.cpython-313-x86_64-linux-gnu.so | accountingDiffTolerated.part.0 |
| 0.01% | _heapq.cpython-313-x86_64-linux-gnu.so | siftup |
| 0.01% | _decimal.cpython-313-x86_64-linux-gnu.so | _mpd_baseshiftr |
| 0.01% | pyexpat.cpython-313-x86_64-linux-gnu.so | normal_nameLength |
| 0.01% | _elementtree.cpython-313-x86_64-linux-gnu.so | expat_end_handler |
| 0.01% | libpthread-2.31.so | sem_trywait@@GLIBC_2.2.5 |
| 0.01% | _asyncio.cpython-313-x86_64-linux-gnu.so | TaskStepMethWrapper_traverse |
| 0.01% | libsqlite3.so.0.8.6 | sqlite3_value_double |
| 0.01% | pyexpat.cpython-313-x86_64-linux-gnu.so | doContent |
| 0.01% | pyexpat.cpython-313-x86_64-linux-gnu.so | lookup.constprop.0 |
| 0.01% | libpython3.11.so.1.0 | PyObject_Malloc |
| 0.01% | _elementtree.cpython-313-x86_64-linux-gnu.so | element_gc_traverse |
| 0.01% | _decimal.cpython-313-x86_64-linux-gnu.so | mpd_qquantize |
| 0.01% | _sqlite3.cpython-313-x86_64-linux-gnu.so | _pysqlite_query_execute |
| 0.01% | _pickle.cpython-313-x86_64-linux-gnu.so | 0x0000000000005e94 |
| 0.01% | math.cpython-313-x86_64-linux-gnu.so | math_sqrt |
| 0.01% | _elementtree.cpython-313-x86_64-linux-gnu.so | treebuilder_handle_start |
| 0.01% | libpthread-2.31.so | sem_post@@GLIBC_2.2.5 |
| 0.01% | libssl.so.1.1 | SSL_rstate_string |
| 0.01% | libpython3.11.so.1.0 | deduce_unreachable |
| 0.01% | _asyncio.cpython-313-x86_64-linux-gnu.so | FutureObj_traverse |
| 0.01% | _asyncio.cpython-313-x86_64-linux-gnu.so | future_init |
| 0.01% | libpython3.11.so.1.0 | visit_decref |
| 0.01% | _decimal.cpython-313-x86_64-linux-gnu.so | PyDecType_New |
| 0.01% | libsqlite3.so.0.8.6 | sqlite3_preupdate_old |
| 0.01% | _asyncio.cpython-313-x86_64-linux-gnu.so | _asyncio_Task___init__ |
| 0.01% | libsqlite3.so.0.8.6 | sqlite3_value_int64 |
| 0.01% | _decimal.cpython-313-x86_64-linux-gnu.so | dec_addstatus |
| 0.01% | _asyncio.cpython-313-x86_64-linux-gnu.so | task_step |
| 0.01% | array.cpython-313-x86_64-linux-gnu.so | d_setitem |
| 0.01% | _asyncio.cpython-313-x86_64-linux-gnu.so | future_schedule_callbacks |
| 0.01% | _asyncio.cpython-313-x86_64-linux-gnu.so | _asyncio_Future_add_done_callback |
| 0.01% | _decimal.cpython-313-x86_64-linux-gnu.so | dec_dealloc |
| 0.01% | _pickle.cpython-313-x86_64-linux-gnu.so | 0x0000000000006004 |
| 0.01% | array.cpython-313-x86_64-linux-gnu.so | d_getitem |
| 0.01% | _pickle.cpython-313-x86_64-linux-gnu.so | 0x0000000000005be4 |
| 0.01% | libsqlite3.so.0.8.6 | sqlite3_extended_errcode |
| 0.01% | libpython3.11.so.1.0 | PyDict_SetDefault |
| 0.01% | _decimal.cpython-313-x86_64-linux-gnu.so | dec_mpd_qquantize |
| 0.01% | libsqlite3.so.0.8.6 | sqlite3_str_value |
| 0.01% | libpython3.11.so.1.0 | type_new |
| 0.01% | _elementtree.cpython-313-x86_64-linux-gnu.so | elementiter_next |
| 0.01% | libpython3.11.so.1.0 | visit_reachable |
| 0.01% | fastbinary.cpython-312-x86_64-linux-gnu.so | apache::thrift::py::ProtocolBase<apache::thrift::py::BinaryProtocol>::decodeValue |
| 0.01% | libsqlite3.so.0.8.6 | sqlite3_wal_checkpoint |
| 0.01% | _decimal.cpython-313-x86_64-linux-gnu.so | mpd_qshiftr |
| 0.01% | libpython3.11.so.1.0 | gc_collect_main |
| 0.01% | _pickle.cpython-313-x86_64-linux-gnu.so | _Unpickler_New |
| 0.01% | libsqlite3.so.0.8.6 | sqlite3_vtab_config |
| 0.01% | pyexpat.cpython-313-x86_64-linux-gnu.so | normal_getAtts |
| 0.01% | _decimal.cpython-313-x86_64-linux-gnu.so | mpd_qfinalize.part.0 |
| 0.01% | pyexpat.cpython-313-x86_64-linux-gnu.so | sip24_final |
| 0.01% | libpython3.11.so.1.0 | r_object |
| 0.01% | libsqlite3.so.0.8.6 | sqlite3_step |
| 0.01% | _random.cpython-313-x86_64-linux-gnu.so | genrand_uint32 |

### dynamic

5.62% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 0.36% | python | PyObject_GenericGetAttr |
| 0.29% | python | PyObject_Hash |
| 0.27% | python | PyType_IsSubtype |
| 0.27% | python | PyObject_RichCompareBool |
| 0.27% | python | _PyObject_GetMethod |
| 0.23% | python | PyObject_GetAttr |
| 0.19% | python | PyNumber_AsSsize_t |
| 0.18% | python | _PyObject_GenericGetAttrWithDict |
| 0.17% | python | _PyObject_MakeTpCall |
| 0.15% | python | PyObject_Vectorcall |
| 0.15% | python | PyObject_Malloc |
| 0.14% | python | PyObject_IsTrue |
| 0.14% | python | type_ready |
| 0.13% | python | PyType_GetModuleByDef |
| 0.13% | python | PyObject_VisitManagedDict |
| 0.11% | python | PyObject_Free |
| 0.11% | python | _PyObject_GetInstanceAttribute |
| 0.11% | python | PyObject_GetItem |
| 0.11% | python | _PyType_GetDict |
| 0.08% | python | PySequence_Contains |
| 0.08% | python | type_call |
| 0.07% | python | PyObject_GetIter |
| 0.07% | python | PyObject_RichCompare |
| 0.07% | python | _PyObject_GenericSetAttrWithDict |
| 0.07% | python | PyObject_GetOptionalAttr |
| 0.06% | python | _PyObject_FreeInstanceAttributes |
| 0.06% | python | _PyObject_Call_Prepend |
| 0.06% | python | getset_get |
| 0.06% | python | PyObject_CallOneArg |
| 0.06% | python | PyObject_Call |
| 0.06% | python | PyObject_SetAttr |
| 0.05% | python | PyObject_SetItem |
| 0.05% | python | PyObject_IsInstance |
| 0.04% | python | PyObject_ClearWeakRefs |
| 0.04% | python | object_isinstance |
| 0.04% | python | PyIter_Next |
| 0.04% | python | _PyObject_LookupSpecial |
| 0.04% | python | do_super_lookup |
| 0.04% | python | PyNumber_Multiply |
| 0.04% | python | PyDescr_IsData |
| 0.04% | python | _Py_type_getattro_impl |
| 0.04% | python | PyObject_Size |
| 0.03% | python | PyNumber_Add |
| 0.03% | python | PyNumber_TrueDivide |
| 0.03% | python | PyObject_VectorcallMethod |
| 0.03% | python | method_get |
| 0.03% | python | PyNumber_And |
| 0.03% | python | _PyObject_InitializeDict |
| 0.03% | python | PyObject_Str |
| 0.03% | python | _PyObject_StoreInstanceAttribute |
| 0.03% | python | StopIteration_init |
| 0.03% | python | PySequence_Fast |
| 0.02% | python | delitem_common |
| 0.02% | python | PyIter_Send |
| 0.02% | python | slot_tp_richcompare |
| 0.02% | python | PyObject_GenericSetAttr |
| 0.02% | python | _PySuper_Lookup |
| 0.02% | python | PyNumber_Subtract |
| 0.02% | python | PyNumber_Remainder |
| 0.02% | python | PySequence_Tuple |
| 0.02% | python | PyNumber_Index |
| 0.01% | python | object_richcompare |
| 0.01% | python | _PyObject_LookupAttr |
| 0.01% | python | _PyNumber_Index |
| 0.01% | python | _PyObject_CallFunctionVa |
| 0.01% | python | PyNumber_Xor |
| 0.01% | python | _PyObject_InitInlineValues |
| 0.01% | python | PyNumber_FloorDivide |
| 0.01% | python | PyNumber_Rshift |
| 0.01% | python | object_vacall |
| 0.01% | python | PyNumber_InPlaceAdd |
| 0.01% | python | object_get_class |
| 0.01% | python | type_mro_modified |
| 0.01% | python | PyObject_IsSubclass |
| 0.01% | python | PyObject_LengthHint |
| 0.01% | python | PyObject_ClearManagedDict |
| 0.01% | python | PyObject_DelItem |
| 0.01% | python | object_init |
| 0.01% | python | PyMapping_Check |
| 0.01% | python | object_recursive_isinstance |
| 0.01% | python | PyObject_GetBuffer |
| 0.01% | python | PyMapping_GetOptionalItem |
| 0.01% | python | PyNumber_Long |

### lookup

4.64% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 1.84% | python | unicodekeys_lookup_unicode |
| 1.25% | python | _Py_dict_lookup |
| 0.87% | python | _PyType_Lookup |
| 0.25% | python | update_one_slot |
| 0.24% | python | find_name_in_mro |
| 0.14% | python | _Py_type_getattro |
| 0.02% | python | builtin_getattr |
| 0.01% | python | PyMember_GetOne |
| 0.01% | python | PyMember_SetOne |

### kernel

4.04% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 0.62% | [kernel.kallsyms] | copy_user_enhanced_fast_string |
| 0.24% | [kernel.kallsyms] | clear_page_erms |
| 0.16% | [kernel.kallsyms] | native_irq_return_iret |
| 0.11% | [kernel.kallsyms] | sync_regs |
| 0.09% | [kernel.kallsyms] | zap_pte_range.isra.0 |
| 0.09% | [kernel.kallsyms] | __d_lookup_rcu |
| 0.08% | [kernel.kallsyms] | rmqueue |
| 0.07% | [kernel.kallsyms] | _raw_spin_lock |
| 0.06% | [kernel.kallsyms] | __handle_mm_fault |
| 0.05% | [kernel.kallsyms] | smp_call_function_single |
| 0.05% | [kernel.kallsyms] | free_pcppages_bulk |
| 0.04% | [kernel.kallsyms] | release_pages |
| 0.04% | [kernel.kallsyms] | copy_pte_range.isra.0 |
| 0.04% | [kernel.kallsyms] | memset_erms |
| 0.04% | [kernel.kallsyms] | try_charge |
| 0.04% | [kernel.kallsyms] | page_remove_rmap |
| 0.04% | [kernel.kallsyms] | link_path_walk.part.0 |
| 0.03% | [kernel.kallsyms] | kmem_cache_alloc |
| 0.03% | [kernel.kallsyms] | copy_page |
| 0.03% | [kernel.kallsyms] | get_mem_cgroup_from_mm |
| 0.03% | [kernel.kallsyms] | __pagevec_lru_add_fn |
| 0.03% | [kernel.kallsyms] | handle_mm_fault |
| 0.03% | [kernel.kallsyms] | filemap_map_pages |
| 0.03% | [kernel.kallsyms] | syscall_return_via_sysret |
| 0.03% | [kernel.kallsyms] | mem_cgroup_throttle_swaprate |
| 0.03% | [kernel.kallsyms] | ext4_htree_store_dirent |
| 0.03% | [kernel.kallsyms] | __ext4fs_dirhash |
| 0.02% | [kernel.kallsyms] | mem_cgroup_try_charge |
| 0.02% | [kernel.kallsyms] | entry_SYSCALL_64 |
| 0.02% | [kernel.kallsyms] | __alloc_pages_nodemask |
| 0.02% | [kernel.kallsyms] | kmem_cache_free |
| 0.02% | [kernel.kallsyms] | do_wp_page |
| 0.02% | [kernel.kallsyms] | do_user_addr_fault |
| 0.02% | [kernel.kallsyms] | strncpy_from_user |
| 0.02% | [kernel.kallsyms] | memcg_kmem_get_cache |
| 0.02% | [kernel.kallsyms] | find_get_entry |
| 0.02% | [kernel.kallsyms] | find_vma |
| 0.02% | [kernel.kallsyms] | page_fault |
| 0.02% | [kernel.kallsyms] | inode_permission |
| 0.02% | [kernel.kallsyms] | filldir64 |
| 0.02% | [kernel.kallsyms] | do_syscall_64 |
| 0.02% | [kernel.kallsyms] | __virt_addr_valid |
| 0.02% | [kernel.kallsyms] | vmacache_find |
| 0.02% | [kernel.kallsyms] | lookup_fast |
| 0.02% | [kernel.kallsyms] | __slab_free |
| 0.02% | [kernel.kallsyms] | __count_memcg_events |
| 0.02% | [kernel.kallsyms] | error_entry |
| 0.02% | [kernel.kallsyms] | memcpy_erms |
| 0.02% | [kernel.kallsyms] | kfree |
| 0.02% | [kernel.kallsyms] | prep_new_page |
| 0.01% | [kernel.kallsyms] | do_anonymous_page |
| 0.01% | [kernel.kallsyms] | generic_permission |
| 0.01% | [kernel.kallsyms] | get_page_from_freelist |
| 0.01% | [kernel.kallsyms] | walk_component |
| 0.01% | [kernel.kallsyms] | perf_iterate_ctx |
| 0.01% | [kernel.kallsyms] | _raw_spin_lock_irqsave |
| 0.01% | [kernel.kallsyms] | str2hashbuf_signed |
| 0.01% | [kernel.kallsyms] | ext4_getattr |
| 0.01% | [kernel.kallsyms] | up_read |
| 0.01% | [kernel.kallsyms] | rb_insert_color |
| 0.01% | [kernel.kallsyms] | __fget_light |
| 0.01% | [kernel.kallsyms] | __mod_memcg_state |
| 0.01% | [kernel.kallsyms] | rb_next |
| 0.01% | [kernel.kallsyms] | __mod_lruvec_state |
| 0.01% | [kernel.kallsyms] | tcp_sendmsg_locked |
| 0.01% | [kernel.kallsyms] | free_pages_and_swap_cache |
| 0.01% | [kernel.kallsyms] | vm_normal_page |
| 0.01% | [kernel.kallsyms] | security_inode_getattr |
| 0.01% | [kernel.kallsyms] | down_read_trylock |
| 0.01% | [kernel.kallsyms] | _cond_resched |
| 0.01% | [kernel.kallsyms] | entry_SYSCALL_64_after_hwframe |
| 0.01% | [kernel.kallsyms] | set_root |
| 0.01% | [kernel.kallsyms] | generic_file_buffered_read |
| 0.01% | [kernel.kallsyms] | psi_task_change |
| 0.01% | [kernel.kallsyms] | swapgs_restore_regs_and_return_to_usermode |
| 0.01% | [kernel.kallsyms] | __vma_adjust |
| 0.01% | [kernel.kallsyms] | xas_load |
| 0.01% | [kernel.kallsyms] | lru_cache_add_active_or_unevictable |
| 0.01% | [kernel.kallsyms] | __lru_cache_add |
| 0.01% | [kernel.kallsyms] | pagevec_lru_move_fn |
| 0.01% | [kernel.kallsyms] | fsnotify |
| 0.01% | [kernel.kallsyms] | __kmalloc |
| 0.01% | [kernel.kallsyms] | __check_object_size |
| 0.01% | [kernel.kallsyms] | __follow_mount_rcu.isra.0 |
| 0.01% | [kernel.kallsyms] | fpregs_assert_state_consistent |
| 0.01% | [kernel.kallsyms] | native_flush_tlb_one_user |
| 0.01% | [kernel.kallsyms] | rcu_all_qs |
| 0.01% | [kernel.kallsyms] | alloc_pages_vma |
| 0.01% | [kernel.kallsyms] | unlock_page |
| 0.01% | [kernel.kallsyms] | mem_cgroup_from_task |
| 0.01% | [kernel.kallsyms] | __mod_node_page_state |
| 0.01% | [kernel.kallsyms] | free_unref_page_prepare.part.0 |
| 0.01% | [kernel.kallsyms] | update_cfs_group |
| 0.01% | [kernel.kallsyms] | security_inode_permission |
| 0.01% | [kernel.kallsyms] | __lock_text_start |
| 0.01% | [kernel.kallsyms] | __tcp_transmit_skb |
| 0.01% | [kernel.kallsyms] | vma_interval_tree_insert |
| 0.01% | [kernel.kallsyms] | in_group_p |
| 0.01% | [kernel.kallsyms] | __legitimize_mnt |
| 0.01% | [kernel.kallsyms] | vma_interval_tree_remove |
| 0.01% | [kernel.kallsyms] | ___slab_alloc |
| 0.01% | [kernel.kallsyms] | free_unref_page_list |
| 0.01% | [kernel.kallsyms] | __mod_zone_page_state |

### unknown

3.34% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 0.16% | python | _Py_hashtable_get_entry_generic |
| 0.09% | python | convertitem.constprop.0 |
| 0.09% | python | _PyThreadState_PushFrame |
| 0.07% | python | call_instrumentation_vector.part.0 |
| 0.07% | python | make_gen |
| 0.07% | python | slot_tp_init |
| 0.06% | python | _PyIO_find_line_ending |
| 0.06% | python | gen_iternext |
| 0.06% | python | memset@plt |
| 0.05% | python | uop_optimize |
| 0.05% | python | compute_range_length |
| 0.05% | python | memcpy@plt |
| 0.05% | python | PyThreadState_GetUnchecked |
| 0.05% | python | func_clear |
| 0.04% | python | PyThread_get_thread_ident |
| 0.04% | python | method_vectorcall |
| 0.04% | python | _PyStack_UnpackDict |
| 0.03% | python | _Py_call_instrumentation_line |
| 0.03% | python | range_iter |
| 0.03% | python | async_gen_asend_iternext |
| 0.03% | python | _PyCfg_OptimizeCodeUnit |
| 0.03% | python | _Py_HashBytes |
| 0.03% | python | min_max |
| 0.03% | python | context_run |
| 0.03% | python | do_mkvalue |
| 0.03% | [vdso] | __vdso_clock_gettime |
| 0.02% | python | sys_audit_tstate |
| 0.02% | python | tok_get_normal_mode |
| 0.02% | python | PyContextVar_Get |
| 0.02% | python | bounded_lru_cache_wrapper |
| 0.02% | python | _Py_MakeCoro |
| 0.02% | python | tailmatch |
| 0.02% | python | tok_nextc |
| 0.02% | python | pysiphash |
| 0.02% | python | hashtable_unicode_compare |
| 0.02% | python | _PyFrame_Copy |
| 0.02% | python | _io_TextIOWrapper_write |
| 0.02% | python | code_hash |
| 0.02% | python | _PyGen_Finalize |
| 0.02% | python | _PyGen_FetchStopIterationValue |
| 0.02% | python | PySys_Audit |
| 0.02% | python | primary_rule |
| 0.02% | python | slot_tp_iternext |
| 0.02% | python | _PyArena_Malloc |
| 0.02% | python | term_rule |
| 0.02% | python | async_gen_anext |
| 0.02% | python | _PyCoro_GetAwaitableIter |
| 0.01% | python | _PyAssemble_MakeCodeObject |
| 0.01% | python | pthread_self@plt |
| 0.01% | python | memcmp@plt |
| 0.01% | python | hashtable_unicode_hash |
| 0.01% | python | range_subscript |
| 0.01% | python | _io_BytesIO_read |
| 0.01% | python | _Py_hashtable_get |
| 0.01% | python | builtin_sum |
| 0.01% | python | build_indices_generic |
| 0.01% | python | PyIndex_Check |
| 0.01% | python | map_next |
| 0.01% | python | countformat |
| 0.01% | python | _Py_bytes_lower |
| 0.01% | python | slot_tp_hash |
| 0.01% | python | _PyModule_ClearDict |
| 0.01% | python | range_vectorcall |
| 0.01% | python | _Py_Specialize_Call |
| 0.01% | python | vectorcall_maybe.constprop.0 |
| 0.01% | python | any_find_slice |
| 0.01% | python | build_string |
| 0.01% | python | _PyThreadState_GetCurrent |
| 0.01% | python | _PyGen_SetStopIterationValue |
| 0.01% | python | builtin_hasattr |
| 0.01% | python | _PyThreadState_MustExit |
| 0.01% | python | _PyThreadState_Attach |
| 0.01% | python | PySet_Add |
| 0.01% | python | _PyFrame_MakeAndSetFrameObject |
| 0.01% | python | _io_open |
| 0.01% | python | convertitem |
| 0.01% | python | _Py_HashPointer |
| 0.01% | python | compiler_visit_expr1 |
| 0.01% | python | lru_cache_make_key |
| 0.01% | python | tok_get |
| 0.01% | python | fill_time |
| 0.01% | python | stringio_iternext |
| 0.01% | python | _PyThreadState_UncheckedGet |
| 0.01% | python | make_dict_from_instance_attributes |
| 0.01% | python | slot_mp_ass_subscript |
| 0.01% | python | unsafe_latin_compare |
| 0.01% | python | mro_implementation |
| 0.01% | python | subtype_clear |
| 0.01% | python | _Py_convert_optional_to_ssize_t |
| 0.01% | python | _Py_Specialize_LoadAttr |
| 0.01% | python | inversion_rule |
| 0.01% | python | vgetargskeywords |
| 0.01% | python | _Py_uop_analyze_and_optimize |
| 0.01% | python | super_getattro |
| 0.01% | python | analyze_descriptor |
| 0.01% | python | sum_rule |
| 0.01% | python | _PyCode_GetCode |
| 0.01% | python | slot_mp_subscript |
| 0.01% | python | shift_expr_rule |
| 0.01% | python | PyContext_CopyCurrent |
| 0.01% | python | unsafe_tuple_compare |
| 0.01% | python | _PyThreadState_Detach |
| 0.01% | python | PyGen_am_send |
| 0.01% | python | mro_internal |
| 0.01% | python | _Py_call_instrumentation_jump |
| 0.01% | python | strlen@plt |
| 0.01% | python | os_stat |
| 0.01% | python | _PyCfg_OptimizedCfgToInstructionSequence |
| 0.01% | python | member_get |
| 0.01% | python | slot_sq_contains |
| 0.01% | python | _abc__abc_instancecheck |
| 0.01% | python | builtin_id |
| 0.01% | python | va_build_value |
| 0.01% | python | assemble |
| 0.01% | python | wrap_descr_get |
| 0.01% | python | _PyType_FromMetaclass_impl |
| 0.01% | python | weakref_hash |
| 0.01% | python | update_slot |
| 0.01% | python | _io_FileIO___init__ |
| 0.01% | python | binary_op1 |
| 0.01% | python | sys_trace_return |
| 0.01% | python | weakref_richcompare |
| 0.01% | python | astfold_expr |
| 0.01% | python | unsafe_long_compare |
| 0.01% | python | slot_tp_iter |
| 0.01% | python | func_descr_get |
| 0.01% | python | symtable_visit_expr |
| 0.01% | python | _Py_slot_tp_getattr_hook |
| 0.01% | python | sys_trace_start |
| 0.01% | python | _PyBytes_Resize |
| 0.01% | python | _PyObjectDict_SetItem |

### libc

3.31% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 2.13% | libc-2.31.so | __nss_database_lookup |
| 0.48% | libc-2.31.so | pthread_attr_setschedparam |
| 0.32% | libcrypto.so.1.1 | CRYPTO_secure_actual_size |
| 0.12% | libc-2.31.so | malloc |
| 0.04% | libc-2.31.so | free |
| 0.02% | libc-2.31.so | pthread_self |
| 0.02% | libc-2.31.so | __gconv_get_alias_db |
| 0.02% | libc-2.31.so | wcsrtombs |
| 0.02% | libc-2.31.so | clock_gettime |
| 0.01% | libc-2.31.so | __libc_realloc |
| 0.01% | libc-2.31.so | _dl_addr |

### int

3.19% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 0.65% | python | k_mul |
| 0.38% | python | x_divrem |
| 0.27% | python | _PyLong_Add |
| 0.20% | python | PyLong_FromLong |
| 0.18% | python | long_hash |
| 0.15% | python | x_add |
| 0.13% | python | PyLong_AsLongAndOverflow |
| 0.11% | python | PyLong_AsSsize_t |
| 0.10% | python | _PyLong_Subtract |
| 0.10% | python | long_to_decimal_string_internal |
| 0.09% | python | x_sub |
| 0.08% | python | long_richcompare |
| 0.08% | python | long_bitwise |
| 0.08% | python | PyLong_FromString |
| 0.07% | python | PyLong_FromSsize_t |
| 0.04% | python | _PyLong_Multiply |
| 0.04% | python | PyLong_AsDouble |
| 0.04% | python | long_rshift1 |
| 0.04% | python | l_mod |
| 0.04% | python | long_div |
| 0.04% | python | long_and |
| 0.03% | python | PyLong_AsLong |
| 0.02% | python | long_rshift |
| 0.02% | python | long_mul |
| 0.02% | python | long_add |
| 0.02% | python | PyLong_FromVoidPtr |
| 0.02% | python | long_lshift1 |
| 0.02% | python | long_xor |
| 0.01% | python | long_lshift |
| 0.01% | python | PyLong_FromUnsignedLong |
| 0.01% | python | _PyLong_GCD |
| 0.01% | python | long_to_decimal_string |
| 0.01% | python | PyLong_FromLongLong |
| 0.01% | python | long_mod |
| 0.01% | python | PyLong_AsInt |
| 0.01% | python | long_float |
| 0.01% | python | _PyLong_Frexp |
| 0.01% | python | long_neg |

### dict

2.56% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 0.40% | python | insertdict |
| 0.31% | python | PyDict_GetItemRef |
| 0.23% | python | PyDict_Next |
| 0.21% | python | free_keys_object |
| 0.17% | python | _PyDict_GetItem_KnownHash |
| 0.13% | python | PyDict_SetDefault |
| 0.13% | python | find_empty_slot |
| 0.10% | python | build_indices_unicode |
| 0.09% | python | insert_to_emptydict |
| 0.09% | python | dict_get |
| 0.08% | python | _PyDict_FromItems |
| 0.07% | python | PyDict_SetItem |
| 0.07% | python | new_keys_object |
| 0.07% | python | PyDict_GetItemWithError |
| 0.04% | python | dictiter_iternextitem |
| 0.04% | python | dictresize |
| 0.04% | python | dict_ass_sub |
| 0.03% | python | dict_merge |
| 0.03% | python | PyDict_Contains |
| 0.03% | python | dict_subscript |
| 0.02% | python | _PyDict_SetItem_Take2 |
| 0.02% | python | _PyDict_LoadGlobal |
| 0.02% | python | clone_combined_dict_keys.isra.0 |
| 0.02% | python | PyDict_GetItem |
| 0.02% | python | _PyDict_Next.part.0 |
| 0.01% | python | _PyDict_DelItem_KnownHash |
| 0.01% | python | dictiter_iternextkey |
| 0.01% | python | dictiter_iternextvalue |

### str

2.55% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 0.47% | python | siphash13 |
| 0.15% | python | ascii_decode |
| 0.14% | python | _PyUnicode_FromUCS1.part.0 |
| 0.13% | python | _PyUnicode_JoinArray.part.0 |
| 0.13% | python | unicode_decode_utf8 |
| 0.10% | python | replace |
| 0.10% | python | _copy_characters.part.0.constprop.0 |
| 0.09% | python | PyUnicode_Substring |
| 0.08% | python | _PyUnicode_InternInPlace |
| 0.06% | python | resize_compact |
| 0.06% | python | _PyUnicode_FromUCS4.part.0 |
| 0.05% | python | _PyUnicode_Equal |
| 0.05% | python | PyBytes_FromStringAndSize |
| 0.05% | python | _PyUnicodeWriter_WriteStr |
| 0.05% | python | PyUnicode_Contains |
| 0.05% | python | PyUnicode_Format |
| 0.05% | python | PyUnicode_RichCompare |
| 0.05% | python | PyUnicode_FromFormatV |
| 0.04% | python | PyUnicode_AsUTF8AndSize |
| 0.04% | python | PyUnicode_InternInPlace |
| 0.03% | python | unicode_hash (inlined) |
| 0.03% | python | unicode_replace |
| 0.03% | python | split |
| 0.03% | python | _PyUnicodeWriter_PrepareInternal |
| 0.02% | python | PyUnicode_AsUCS4 |
| 0.02% | python | bytes_subscript |
| 0.02% | python | PyUnicode_Concat |
| 0.02% | python | unicode_startswith |
| 0.02% | python | stringlib_bytes_join |
| 0.01% | python | unicode_subscript |
| 0.01% | python | _PyUnicodeWriter_WriteSubstring.part.0 |
| 0.01% | python | unicode_lower |
| 0.01% | python | unicode_rstrip |
| 0.01% | python | PyUnicode_FromWideChar |
| 0.01% | python | _PyUnicodeWriter_WriteASCIIString |
| 0.01% | python | PyUnicode_Decode.part.0 |
| 0.01% | python | PyUnicode_FromKindAndData |
| 0.01% | python | unicode_join |
| 0.01% | python | PyBytes_Repr |
| 0.01% | python | unicode_encode_utf8 |
| 0.01% | python | unicode_endswith |
| 0.01% | python | PyUnicode_AsEncodedString.part.0 |
| 0.01% | python | _PyUnicodeWriter_Init |
| 0.01% | python | _PyUnicodeWriter_Finish |
| 0.01% | python | unicode_hash |
| 0.01% | python | PyUnicode_InternFromString |
| 0.01% | python | _PyUnicode_ToLowercase |
| 0.01% | python | unicode_rpartition |
| 0.01% | python | _PyUnicode_IsAlpha |
| 0.01% | python | bytes_concat |
| 0.01% | python | _PyUnicode_TranslateCharmap |
| 0.01% | python | PyUnicode_Splitlines |
| 0.01% | python | bytes_richcompare |
| 0.01% | python | unicode_repr |
| 0.01% | python | PyUnicode_FromEncodedObject |
| 0.01% | python | PyUnicode_CompareWithASCIIString |

### miscobj

1.23% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 0.24% | python | set_lookkey |
| 0.18% | python | PySlice_AdjustIndices |
| 0.11% | python | _PyBuildSlice_ConsumeRefs |
| 0.10% | python | set_add_entry |
| 0.09% | python | setiter_iternext |
| 0.08% | python | set_issubset |
| 0.05% | python | PySlice_Unpack |
| 0.04% | python | set_difference |
| 0.03% | python | set_contains |
| 0.03% | python | PyBool_FromLong |
| 0.03% | python | set_update_internal |
| 0.03% | python | deque_append |
| 0.03% | python | set_table_resize |
| 0.03% | python | enum_next |
| 0.02% | python | PyBuffer_Release |
| 0.02% | python | dequeiter_next |
| 0.02% | python | bytearray_ass_subscript |
| 0.01% | python | PyBuffer_FillInfo |
| 0.01% | python | deque_popleft |
| 0.01% | python | set_intersection |
| 0.01% | python | _PySlice_GetLongIndices |
| 0.01% | python | deque_clear.part.0 |
| 0.01% | python | set_richcompare |

### tuple

0.98% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 0.36% | python | tuplehash |
| 0.17% | python | _PyTuple_FromArray |
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

### list

0.95% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 0.21% | python | list_ass_slice |
| 0.11% | python | list_subscript |
| 0.07% | python | list_extend |
| 0.07% | python | list_slice.isra.0 |
| 0.06% | python | PyList_Append |
| 0.06% | python | _PyList_FromArraySteal |
| 0.05% | python | list_iter |
| 0.05% | python | listiter_next |
| 0.04% | python | list_sort_impl |
| 0.04% | python | list_concat |
| 0.04% | python | list_contains |
| 0.03% | python | list_append |
| 0.03% | python | list_ass_subscript |
| 0.02% | python | _PyList_AppendTakeRefListResize |
| 0.02% | python | list_pop |
| 0.01% | python | list_insert |
| 0.01% | python | list_length |
| 0.01% | python | PyList_Size |

### calls

0.62% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 0.11% | python | vgetargs1_impl |
| 0.08% | python | _PyFunction_Vectorcall |
| 0.07% | python | _Py_CheckFunctionResult |
| 0.07% | python | vgetargskeywords.constprop.0 |
| 0.03% | python | _PyArg_UnpackKeywords |
| 0.03% | python | PyArg_UnpackTuple |
| 0.03% | python | method_vectorcall_VARARGS |
| 0.02% | python | cfunction_vectorcall_FASTCALL_KEYWORDS |
| 0.02% | python | method_vectorcall_FASTCALL_KEYWORDS_METHOD |
| 0.02% | python | cfunction_vectorcall_NOARGS |
| 0.02% | python | cfunction_call |
| 0.01% | python | PyArg_ParseTuple |
| 0.01% | python | PyArg_ParseTupleAndKeywords |
| 0.01% | python | cfunction_vectorcall_O |
| 0.01% | python | _PyArg_UnpackKeywordsWithVararg |
| 0.01% | python | method_vectorcall_NOARGS |
| 0.01% | python | vectorcall_method |
| 0.01% | python | method_vectorcall_VARARGS_KEYWORDS |
| 0.01% | python | PyArg_Parse |
| 0.01% | python | method_vectorcall_FASTCALL |
| 0.01% | python | method_vectorcall_O |
| 0.01% | python | cfunction_vectorcall_FASTCALL_KEYWORDS_METHOD |

### exceptions

0.56% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 0.13% | python | _PyErr_SetObject.part.0 |
| 0.07% | python | PyErr_CheckSignals |
| 0.07% | python | PyErr_Occurred |
| 0.07% | python | PyCode_Addr2Line |
| 0.03% | python | PyErr_ExceptionMatches |
| 0.03% | python | PyTraceBack_Here |
| 0.03% | python | _PyErr_Restore |
| 0.02% | python | _PyErr_ExceptionMatches |
| 0.01% | python | BaseException_init |
| 0.01% | python | BaseException_clear |
| 0.01% | python | _PyErr_CreateException |
| 0.01% | python | PyErr_GetRaisedException |
| 0.01% | python | PyErr_SetRaisedException |
| 0.01% | python | AttributeError_init |
| 0.01% | python | PyException_GetTraceback |
| 0.01% | python | _PyErr_SetKeyError |

### float

0.38% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 0.17% | python | PyFloat_FromDouble |
| 0.08% | python | float_div |
| 0.03% | python | float_richcompare |
| 0.03% | python | float_mul |
| 0.02% | python | float_sub |
| 0.02% | python | float_pow |
| 0.01% | python | float_rem |
| 0.01% | python | PyFloat_AsDouble.part.0 |
| 0.01% | python | PyFloat_AsDouble |
| 0.01% | python | float_add |

### import

0.36% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 0.30% | python | r_object |
| 0.02% | python | r_string (inlined) |
| 0.02% | python | PyImport_ImportModuleLevelObject |
| 0.01% | python | r_byte |

### gil

0.07% total

| percentage | object | symbol |
| ---: | :--- | :--- |
| 0.05% | python | take_gil |
| 0.02% | python | drop_gil |
