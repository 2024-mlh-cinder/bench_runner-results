
# Pystats results

- benchmark: dulwich_log
- fork: faster-cpython
- ref: tier-2-exponential-backoff
- commit hash: bf453f8
- commit date: 2023-11-02T14:05:18+00:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 52,643,400 | 20.3% | 20.3% |  |
| LOAD_CONST | 21,520,140 | 8.3% | 28.7% |  |
| STORE_FAST | 15,107,400 | 5.8% | 34.5% |  |
| POP_JUMP_IF_FALSE | 12,546,980 | 4.8% | 39.3% |  |
| RESUME_CHECK | 10,778,460 | 4.2% | 43.5% |  |
| RETURN_VALUE | 8,406,480 | 3.2% | 46.8% |  |
| LOAD_ATTR_METHOD_NO_DICT | 8,356,640 | 3.2% | 50.0% |  |
| LOAD_FAST_LOAD_FAST | 7,603,360 | 2.9% | 52.9% |  |
| LOAD_ATTR_INSTANCE_VALUE | 7,571,960 | 2.9% | 55.8% |  |
| LOAD_GLOBAL_MODULE | 7,250,860 | 2.8% | 58.6% |  |
| CALL_PY_EXACT_ARGS | 6,110,620 | 2.4% | 61.0% |  |
| STORE_ATTR_SLOT | 5,253,660 | 2.0% | 63.0% |  |
| LOAD_GLOBAL_BUILTIN | 5,247,420 | 2.0% | 65.1% | 0.0% |
| LOAD_ATTR_SLOT | 4,604,900 | 1.8% | 66.8% |  |
| TO_BOOL_BOOL | 4,465,720 | 1.7% | 68.6% | 0.7% |
| COMPARE_OP | 4,105,120 | 1.6% | 70.2% |  |
| POP_TOP | 3,345,100 | 1.3% | 71.5% |  |
| COMPARE_OP_INT | 3,051,680 | 1.2% | 72.6% |  |
| BINARY_OP_ADD_INT | 2,830,900 | 1.1% | 73.7% |  |
| POP_JUMP_IF_NONE | 2,743,500 | 1.1% | 74.8% |  |
| STORE_FAST_STORE_FAST | 2,503,860 | 1.0% | 75.8% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 2,491,920 | 1.0% | 76.7% |  |
| BINARY_SLICE | 2,429,740 | 0.9% | 77.7% |  |
| CALL | 2,387,440 | 0.9% | 78.6% |  |
| PUSH_NULL | 2,301,180 | 0.9% | 79.5% |  |
| BUILD_TUPLE | 2,252,680 | 0.9% | 80.3% |  |
| BINARY_OP | 2,061,300 | 0.8% | 81.1% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 2,001,800 | 0.8% | 81.9% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 1,992,840 | 0.8% | 82.7% |  |
| POP_JUMP_IF_TRUE | 1,876,840 | 0.7% | 83.4% |  |
| NOP | 1,871,480 | 0.7% | 84.1% |  |
| LOAD_DEREF | 1,862,120 | 0.7% | 84.8% |  |
| RETURN_CONST | 1,748,900 | 0.7% | 85.5% |  |
| BINARY_OP_MULTIPLY_INT | 1,551,180 | 0.6% | 86.1% |  |
| JUMP_BACKWARD | 1,505,320 | 0.6% | 86.7% |  |
| BUILD_LIST | 1,501,860 | 0.6% | 87.3% |  |
| FOR_ITER | 1,501,760 | 0.6% | 87.9% |  |
| CALL_LEN | 1,499,980 | 0.6% | 88.4% |  |
| LOAD_ATTR_PROPERTY | 1,493,600 | 0.6% | 89.0% |  |
| POP_JUMP_IF_NOT_NONE | 1,373,980 | 0.5% | 89.5% |  |
| CALL_BUILTIN_CLASS | 1,373,940 | 0.5% | 90.1% |  |
| CONTAINS_OP | 1,371,960 | 0.5% | 90.6% |  |
| LOAD_ATTR_MODULE | 1,370,420 | 0.5% | 91.1% | 0.0% |
| STORE_ATTR_INSTANCE_VALUE | 1,368,180 | 0.5% | 91.7% |  |
| JUMP_FORWARD | 1,174,280 | 0.5% | 92.1% |  |
| TO_BOOL | 1,003,140 | 0.4% | 92.5% |  |
| CALL_BUILTIN_O | 876,040 | 0.3% | 92.8% |  |
| COPY | 875,200 | 0.3% | 93.2% |  |
| GET_ITER | 874,780 | 0.3% | 93.5% |  |
| CALL_METHOD_DESCRIPTOR_O | 871,200 | 0.3% | 93.9% | 0.0% |
| FOR_ITER_GEN | 751,820 | 0.3% | 94.2% |  |
| UNPACK_SEQUENCE_LIST | 751,800 | 0.3% | 94.4% |  |
| INTERPRETER_EXIT | 749,740 | 0.3% | 94.7% |  |
| CALL_BUILTIN_FAST | 748,920 | 0.3% | 95.0% |  |
| ENTER_EXECUTOR | 679,040 | 0.3% | 95.3% |  |
| LOAD_ATTR | 635,640 | 0.2% | 95.5% |  |
| CALL_LIST_APPEND | 631,900 | 0.2% | 95.8% |  |
| YIELD_VALUE | 626,760 | 0.2% | 96.0% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 549,620 | 0.2% | 96.2% | 0.0% |
| TO_BOOL_INT | 531,780 | 0.2% | 96.4% | 5.7% |
| BINARY_SUBSCR | 501,600 | 0.2% | 96.6% |  |
| CALL_ISINSTANCE | 499,900 | 0.2% | 96.8% |  |
| CALL_KW | 499,700 | 0.2% | 97.0% |  |
| BINARY_SUBSCR_LIST_INT | 499,680 | 0.2% | 97.2% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 499,640 | 0.2% | 97.4% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 498,800 | 0.2% | 97.6% | 0.0% |
| UNPACK_SEQUENCE_TUPLE | 375,380 | 0.1% | 97.7% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 374,340 | 0.1% | 97.9% |  |
| CALL_PY_WITH_DEFAULTS | 374,240 | 0.1% | 98.0% |  |
| COPY_FREE_VARS | 373,700 | 0.1% | 98.2% |  |
| CHECK_EXC_MATCH | 373,380 | 0.1% | 98.3% |  |
| POP_EXCEPT | 373,380 | 0.1% | 98.5% |  |
| PUSH_EXC_INFO | 373,380 | 0.1% | 98.6% |  |
| BINARY_OP_SUBTRACT_INT | 321,920 | 0.1% | 98.7% |  |
| UNARY_NEGATIVE | 277,700 | 0.1% | 98.8% |  |
| BINARY_SUBSCR_GETITEM | 250,260 | 0.1% | 98.9% |  |
| LOAD_ATTR_METHOD_LAZY_DICT | 250,200 | 0.1% | 99.0% |  |
| SWAP | 249,840 | 0.1% | 99.1% |  |
| BINARY_SUBSCR_DICT | 249,440 | 0.1% | 99.2% |  |
| BINARY_OP_ADD_UNICODE | 248,500 | 0.1% | 99.3% |  |
| MAKE_FUNCTION | 125,760 | 0.0% | 99.4% |  |
| BINARY_SUBSCR_TUPLE_INT | 125,500 | 0.0% | 99.4% |  |
| RETURN_GENERATOR | 125,160 | 0.0% | 99.5% |  |
| LOAD_SUPER_ATTR_METHOD | 125,140 | 0.0% | 99.5% |  |
| END_FOR | 125,120 | 0.0% | 99.6% |  |
| MAKE_CELL | 124,780 | 0.0% | 99.6% |  |
| FOR_ITER_LIST | 124,720 | 0.0% | 99.7% |  |
| EXTENDED_ARG | 124,640 | 0.0% | 99.7% |  |
| TO_BOOL_STR | 124,440 | 0.0% | 99.8% |  |
| BUILD_MAP | 124,320 | 0.0% | 99.8% |  |
| EXIT_INIT_CHECK | 124,280 | 0.0% | 99.8% |  |
| CALL_ALLOC_AND_ENTER_INIT | 124,280 | 0.0% | 99.9% |  |
| TO_BOOL_LIST | 124,240 | 0.0% | 99.9% |  |
| BINARY_OP_INPLACE_ADD_UNICODE | 124,220 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 5,880 | 0.0% | 100.0% |  |
| STORE_ATTR | 4,920 | 0.0% | 100.0% |  |
| RESUME | 1,960 | 0.0% | 100.0% |  |
| FOR_ITER_RANGE | 1,740 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE | 1,020 | 0.0% | 100.0% |  |
| STORE_NAME | 840 | 0.0% | 100.0% |  |
| IS_OP | 620 | 0.0% | 100.0% |  |
| TO_BOOL_NONE | 240 | 0.0% | 100.0% | 16.7% |
| SET_FUNCTION_ATTRIBUTE | 240 | 0.0% | 100.0% |  |
| CALL_FUNCTION_EX | 220 | 0.0% | 100.0% |  |
| IMPORT_FROM | 220 | 0.0% | 100.0% |  |
| LOAD_NAME | 220 | 0.0% | 100.0% |  |
| BEFORE_WITH | 200 | 0.0% | 100.0% |  |
| IMPORT_NAME | 200 | 0.0% | 100.0% |  |
| STORE_SUBSCR | 180 | 0.0% | 100.0% |  |
| LOAD_FAST_CHECK | 180 | 0.0% | 100.0% |  |
| STORE_SUBSCR_DICT | 180 | 0.0% | 100.0% |  |
| DICT_MERGE | 140 | 0.0% | 100.0% |  |
| STORE_FAST_LOAD_FAST | 140 | 0.0% | 100.0% |  |
| COMPARE_OP_STR | 140 | 0.0% | 100.0% |  |
| LIST_APPEND | 120 | 0.0% | 100.0% |  |
| LOAD_FAST_AND_CLEAR | 120 | 0.0% | 100.0% |  |
| FOR_ITER_TUPLE | 120 | 0.0% | 100.0% |  |
| CALL_INTRINSIC_1 | 100 | 0.0% | 100.0% |  |
| LIST_EXTEND | 100 | 0.0% | 100.0% |  |
| LOAD_BUILD_CLASS | 60 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR | 60 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_FLOAT | 60 | 0.0% | 100.0% |  |
| CALL_STR_1 | 60 | 0.0% | 100.0% |  |
| BUILD_CONST_KEY_MAP | 40 | 0.0% | 100.0% |  |
| DELETE_SUBSCR | 20 | 0.0% | 100.0% |  |
| CALL_TUPLE_1 | 20 | 0.0% | 100.0% |  |
| CALL_TYPE_1 | 20 | 0.0% | 100.0% |  |
| COMPARE_OP_FLOAT | 20 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| POP_JUMP_IF_FALSE LOAD_FAST | 7,926,960 | 3.1% | 3.1% |
| LOAD_FAST LOAD_CONST | 7,208,400 | 2.8% | 5.8% |
| STORE_FAST LOAD_FAST | 7,130,300 | 2.8% | 8.6% |
| RESUME_CHECK LOAD_FAST | 6,407,520 | 2.5% | 11.1% |
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 5,955,360 | 2.3% | 13.4% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 5,861,300 | 2.3% | 15.6% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 4,500,380 | 1.7% | 17.4% |
| LOAD_FAST LOAD_ATTR_SLOT | 4,479,500 | 1.7% | 19.1% |
| LOAD_FAST STORE_ATTR_SLOT | 4,127,360 | 1.6% | 20.7% |
| COMPARE_OP POP_JUMP_IF_FALSE | 4,004,000 | 1.5% | 22.3% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 3,999,820 | 1.5% | 23.8% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_CONST | 3,870,620 | 1.5% | 25.3% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 3,869,000 | 1.5% | 26.8% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 3,247,480 | 1.3% | 28.0% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 2,879,700 | 1.1% | 29.2% |
| LOAD_CONST CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 2,491,840 | 1.0% | 30.1% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 2,415,000 | 0.9% | 31.1% |
| LOAD_CONST LOAD_CONST | 2,256,440 | 0.9% | 31.9% |
| LOAD_GLOBAL_MODULE COMPARE_OP | 2,254,360 | 0.9% | 32.8% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 1,996,120 | 0.8% | 33.6% |
| STORE_ATTR_SLOT LOAD_FAST | 1,876,460 | 0.7% | 34.3% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 1,875,220 | 0.7% | 35.0% |
| LOAD_ATTR_METHOD_NO_DICT CALL_PY_EXACT_ARGS | 1,865,040 | 0.7% | 35.7% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 1,800,240 | 0.7% | 36.4% |
| LOAD_CONST LOAD_FAST | 1,754,500 | 0.7% | 37.1% |
| LOAD_CONST COMPARE_OP_INT | 1,751,620 | 0.7% | 37.8% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST_STORE_FAST | 1,751,600 | 0.7% | 38.5% |
| POP_JUMP_IF_NONE LOAD_FAST | 1,743,300 | 0.7% | 39.1% |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS RETURN_VALUE | 1,740,120 | 0.7% | 39.8% |
| RETURN_VALUE LOAD_ATTR_METHOD_NO_DICT | 1,740,080 | 0.7% | 40.5% |
| LOAD_CONST STORE_FAST | 1,723,460 | 0.7% | 41.2% |
| PUSH_NULL LOAD_FAST | 1,675,080 | 0.6% | 41.8% |
| RETURN_VALUE STORE_FAST | 1,674,120 | 0.6% | 42.4% |
| LOAD_CONST BINARY_SLICE | 1,628,180 | 0.6% | 43.1% |
| LOAD_CONST BINARY_OP_ADD_INT | 1,528,180 | 0.6% | 43.7% |
| LOAD_CONST BINARY_OP | 1,503,860 | 0.6% | 44.2% |
| NOP LOAD_FAST | 1,496,420 | 0.6% | 44.8% |
| LOAD_FAST LOAD_ATTR_PROPERTY | 1,493,360 | 0.6% | 45.4% |
| POP_TOP LOAD_FAST | 1,470,720 | 0.6% | 46.0% |
| LOAD_CONST CALL | 1,379,540 | 0.5% | 46.5% |
| CALL TO_BOOL_BOOL | 1,376,720 | 0.5% | 47.0% |
| STORE_FAST LOAD_CONST | 1,376,620 | 0.5% | 47.6% |
| LOAD_FAST LOAD_FAST | 1,376,100 | 0.5% | 48.1% |
| LOAD_FAST POP_JUMP_IF_NONE | 1,375,620 | 0.5% | 48.6% |
| LOAD_FAST CALL_LEN | 1,375,620 | 0.5% | 49.2% |
| LOAD_ATTR_PROPERTY RESUME_CHECK | 1,369,460 | 0.5% | 49.7% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 1,301,460 | 0.5% | 50.2% |
| LOAD_FAST_LOAD_FAST LOAD_CONST | 1,301,160 | 0.5% | 50.7% |
| LOAD_CONST BINARY_OP_MULTIPLY_INT | 1,300,780 | 0.5% | 51.2% |
| STORE_FAST_STORE_FAST LOAD_FAST | 1,251,420 | 0.5% | 51.7% |
| STORE_FAST LOAD_GLOBAL_BUILTIN | 1,251,200 | 0.5% | 52.2% |
| BUILD_TUPLE RETURN_VALUE | 1,251,180 | 0.5% | 52.7% |
| LOAD_FAST STORE_FAST | 1,250,300 | 0.5% | 53.1% |
| CONTAINS_OP POP_JUMP_IF_FALSE | 1,247,660 | 0.5% | 53.6% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 1,246,300 | 0.5% | 54.1% |
| LOAD_DEREF LOAD_ATTR_INSTANCE_VALUE | 1,241,800 | 0.5% | 54.6% |
| BINARY_OP_ADD_INT STORE_FAST | 1,153,020 | 0.4% | 55.0% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_SLOT | 1,125,140 | 0.4% | 55.5% |
| STORE_FAST LOAD_GLOBAL_MODULE | 1,124,820 | 0.4% | 55.9% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 1,124,240 | 0.4% | 56.3% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 1,121,880 | 0.4% | 56.8% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 1,121,680 | 0.4% | 57.2% |
| LOAD_ATTR_SLOT RETURN_VALUE | 1,119,280 | 0.4% | 57.6% |
| BINARY_SLICE RETURN_VALUE | 1,051,040 | 0.4% | 58.0% |
| BINARY_OP STORE_FAST | 1,050,900 | 0.4% | 58.4% |
| CALL_LEN LOAD_CONST | 1,000,840 | 0.4% | 58.8% |
| STORE_ATTR_SLOT LOAD_CONST | 1,000,640 | 0.4% | 59.2% |
| FOR_ITER STORE_FAST | 1,000,480 | 0.4% | 59.6% |
| POP_JUMP_IF_NOT_NONE LOAD_FAST | 999,500 | 0.4% | 60.0% |
| LOAD_CONST COMPARE_OP | 974,300 | 0.4% | 60.4% |
| POP_JUMP_IF_FALSE LOAD_FAST_LOAD_FAST | 947,500 | 0.4% | 60.7% |
| BINARY_OP_MULTIPLY_INT BINARY_OP_ADD_INT | 925,280 | 0.4% | 61.1% |
| LOAD_FAST TO_BOOL | 876,400 | 0.3% | 61.4% |
| RETURN_VALUE UNPACK_SEQUENCE_TWO_TUPLE | 875,480 | 0.3% | 61.8% |
| JUMP_BACKWARD FOR_ITER | 875,320 | 0.3% | 62.1% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 874,000 | 0.3% | 62.4% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_MODULE | 872,880 | 0.3% | 62.8% |
| LOAD_FAST TO_BOOL_BOOL | 872,520 | 0.3% | 63.1% |
| RETURN_VALUE RETURN_VALUE | 872,420 | 0.3% | 63.4% |
| LOAD_FAST_LOAD_FAST COMPARE_OP | 872,260 | 0.3% | 63.8% |
| LOAD_ATTR_SLOT POP_JUMP_IF_NONE | 870,080 | 0.3% | 64.1% |
| LOAD_ATTR_SLOT LOAD_ATTR_METHOD_NO_DICT | 870,040 | 0.3% | 64.5% |
| LOAD_ATTR_SLOT TO_BOOL_BOOL | 870,040 | 0.3% | 64.8% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_NO_DICT | 869,840 | 0.3% | 65.1% |
| BINARY_OP_ADD_INT BINARY_SLICE | 801,280 | 0.3% | 65.4% |
| LOAD_FAST PUSH_NULL | 800,500 | 0.3% | 65.7% |
| UNPACK_SEQUENCE_LIST STORE_FAST_STORE_FAST | 751,800 | 0.3% | 66.0% |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS UNPACK_SEQUENCE_LIST | 751,760 | 0.3% | 66.3% |
| CALL STORE_FAST | 751,260 | 0.3% | 66.6% |
| BINARY_SLICE STORE_FAST | 751,160 | 0.3% | 66.9% |
| COMPARE_OP_INT POP_JUMP_IF_TRUE | 750,920 | 0.3% | 67.2% |
| BUILD_LIST LOAD_FAST | 750,840 | 0.3% | 67.5% |
| BUILD_LIST STORE_FAST | 750,740 | 0.3% | 67.8% |
| CALL_BUILTIN_CLASS STORE_FAST | 750,680 | 0.3% | 68.1% |
| STORE_ATTR_SLOT RETURN_CONST | 750,520 | 0.3% | 68.4% |
| STORE_FAST JUMP_BACKWARD | 750,180 | 0.3% | 68.7% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 749,480 | 0.3% | 68.9% |
| LOAD_FAST RETURN_VALUE | 749,240 | 0.3% | 69.2% |
| STORE_FAST NOP | 748,980 | 0.3% | 69.5% |
| POP_JUMP_IF_TRUE LOAD_FAST | 748,900 | 0.3% | 69.8% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### BINARY_SLICE

<details>
<summary> Successors and predecessors for BINARY_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,628,180 | 67.0% |
| BINARY_OP_ADD_INT | 801,280 | 33.0% |
| BINARY_OP | 200 | 0.0% |
| LOAD_FAST | 60 | 0.0% |
| UNARY_NEGATIVE | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 1,051,040 | 43.3% |
| STORE_FAST | 751,160 | 30.9% |
| CALL_BUILTIN_CLASS | 375,160 | 15.4% |
| CALL_BUILTIN_O | 251,300 | 10.3% |
| CALL | 440 | 0.0% |


</details>

### CACHE

<details>
<summary> Successors and predecessors for CACHE </summary>

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 499,320 | 66.6% |
| COPY_FREE_VARS | 125,220 | 16.7% |
| MAKE_CELL | 124,660 | 16.6% |
| RESUME | 500 | 0.1% |
| POP_TOP | 60 | 0.0% |


</details>

### BEFORE_WITH

<details>
<summary> Successors and predecessors for BEFORE_WITH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 80 | 40.0% |
| RETURN_VALUE | 60 | 30.0% |
| LOAD_ATTR_INSTANCE_VALUE | 40 | 20.0% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 20 | 10.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 160 | 80.0% |
| STORE_FAST | 40 | 20.0% |


</details>

### BINARY_OP_INPLACE_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_INPLACE_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_UNICODE | 124,220 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 124,220 | 100.0% |


</details>

### BINARY_SUBSCR

<details>
<summary> Successors and predecessors for BINARY_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 500,800 | 99.8% |
| BINARY_SUBSCR | 560 | 0.1% |
| LOAD_FAST | 160 | 0.0% |
| LOAD_FAST_LOAD_FAST | 40 | 0.0% |
| BINARY_OP | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 500,560 | 99.8% |
| BINARY_SUBSCR | 560 | 0.1% |
| STORE_FAST | 100 | 0.0% |
| BINARY_SUBSCR_LIST_INT | 100 | 0.0% |
| RETURN_VALUE | 80 | 0.0% |


</details>

### CHECK_EXC_MATCH

<details>
<summary> Successors and predecessors for CHECK_EXC_MATCH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 373,320 | 100.0% |
| LOAD_GLOBAL | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 373,380 | 100.0% |


</details>

### DELETE_SUBSCR

<details>
<summary> Successors and predecessors for DELETE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 20 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 20 | 100.0% |


</details>

### END_FOR

<details>
<summary> Successors and predecessors for END_FOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 125,120 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 125,120 | 100.0% |


</details>

### EXIT_INIT_CHECK

<details>
<summary> Successors and predecessors for EXIT_INIT_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 124,280 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 124,280 | 100.0% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_CLASS | 374,640 | 42.8% |
| RETURN_VALUE | 249,380 | 28.5% |
| LOAD_FAST | 125,320 | 14.3% |
| RETURN_GENERATOR | 125,120 | 14.3% |
| CALL | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 624,920 | 71.4% |
| FOR_ITER_GEN | 125,100 | 14.3% |
| FOR_ITER_LIST | 124,240 | 14.2% |
| FOR_ITER_RANGE | 360 | 0.0% |
| LOAD_FAST_AND_CLEAR | 120 | 0.0% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 500,800 | 66.8% |
| RETURN_VALUE | 248,880 | 33.2% |
| YIELD_VALUE | 60 | 0.0% |


</details>

### LOAD_BUILD_CLASS

<details>
<summary> Successors and predecessors for LOAD_BUILD_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_NAME | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 60 | 100.0% |


</details>

### MAKE_FUNCTION

<details>
<summary> Successors and predecessors for MAKE_FUNCTION </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 125,760 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 125,180 | 99.5% |
| SET_FUNCTION_ATTRIBUTE | 240 | 0.2% |
| STORE_NAME | 240 | 0.2% |
| LOAD_CONST | 60 | 0.0% |
| BUILD_TUPLE | 20 | 0.0% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 748,980 | 40.0% |
| RESUME_CHECK | 622,180 | 33.2% |
| POP_JUMP_IF_TRUE | 250,360 | 13.4% |
| POP_JUMP_IF_FALSE | 125,180 | 6.7% |
| FOR_ITER | 124,200 | 6.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,496,420 | 80.0% |
| LOAD_GLOBAL_MODULE | 250,420 | 13.4% |
| LOAD_GLOBAL_BUILTIN | 124,180 | 6.6% |
| LOAD_FAST_LOAD_FAST | 160 | 0.0% |
| LOAD_CONST | 100 | 0.0% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 373,340 | 100.0% |
| STORE_FAST | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_FORWARD | 249,160 | 66.7% |
| RETURN_CONST | 124,180 | 33.3% |
| ENTER_EXECUTOR | 40 | 0.0% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 748,740 | 22.4% |
| RESUME_CHECK | 626,720 | 18.7% |
| RETURN_CONST | 626,060 | 18.7% |
| CALL_METHOD_DESCRIPTOR_O | 620,640 | 18.6% |
| SWAP | 125,180 | 3.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,470,720 | 44.0% |
| RETURN_CONST | 374,860 | 11.2% |
| POP_EXCEPT | 373,340 | 11.2% |
| LOAD_CONST | 250,480 | 7.5% |
| RETURN_VALUE | 125,240 | 3.7% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_DICT | 249,160 | 66.7% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 124,180 | 33.3% |
| BINARY_SUBSCR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 373,280 | 100.0% |
| LOAD_GLOBAL | 100 | 0.0% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 800,500 | 34.8% |
| LOAD_ATTR_MODULE | 748,360 | 32.5% |
| LOAD_FAST_LOAD_FAST | 501,600 | 21.8% |
| LOAD_ATTR | 125,400 | 5.4% |
| RETURN_VALUE | 125,120 | 5.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,675,080 | 72.8% |
| LOAD_CONST | 125,820 | 5.5% |
| CALL | 125,580 | 5.5% |
| LOAD_FAST_LOAD_FAST | 125,480 | 5.5% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 124,960 | 5.4% |


</details>

### RETURN_GENERATOR

<details>
<summary> Successors and predecessors for RETURN_GENERATOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 125,100 | 100.0% |
| COPY_FREE_VARS | 40 | 0.0% |
| CALL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 125,120 | 100.0% |
| CALL | 40 | 0.0% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 1,740,120 | 20.7% |
| BUILD_TUPLE | 1,251,180 | 14.9% |
| LOAD_ATTR_SLOT | 1,119,280 | 13.3% |
| BINARY_SLICE | 1,051,040 | 12.5% |
| RETURN_VALUE | 872,420 | 10.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 1,740,080 | 20.7% |
| STORE_FAST | 1,674,120 | 19.9% |
| UNPACK_SEQUENCE_TWO_TUPLE | 875,480 | 10.4% |
| RETURN_VALUE | 872,420 | 10.4% |
| BUILD_TUPLE | 626,600 | 7.5% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 120 | 66.7% |
| LOAD_CONST | 40 | 22.2% |
| STORE_SUBSCR | 20 | 11.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 80 | 44.4% |
| STORE_SUBSCR_DICT | 40 | 22.2% |
| STORE_SUBSCR | 20 | 11.1% |
| JUMP_FORWARD | 20 | 11.1% |
| LOAD_FAST | 20 | 11.1% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 876,400 | 87.4% |
| LOAD_ATTR_INSTANCE_VALUE | 124,280 | 12.4% |
| TO_BOOL | 1,200 | 0.1% |
| CALL | 360 | 0.0% |
| BINARY_OP | 280 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 627,380 | 62.5% |
| POP_JUMP_IF_TRUE | 373,760 | 37.3% |
| TO_BOOL | 1,200 | 0.1% |
| TO_BOOL_BOOL | 540 | 0.1% |
| TO_BOOL_INT | 160 | 0.0% |


</details>

### UNARY_NEGATIVE

<details>
<summary> Successors and predecessors for UNARY_NEGATIVE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 153,520 | 55.3% |
| RETURN_VALUE | 124,140 | 44.7% |
| CALL | 20 | 0.0% |
| LOAD_ATTR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 153,520 | 55.3% |
| LOAD_FAST | 124,160 | 44.7% |
| BINARY_SLICE | 20 | 0.0% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,503,860 | 73.0% |
| ENTER_EXECUTOR | 424,220 | 20.6% |
| BINARY_OP_ADD_INT | 125,540 | 6.1% |
| BINARY_OP | 5,720 | 0.3% |
| LOAD_FAST | 1,020 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,050,900 | 51.0% |
| TO_BOOL_INT | 377,140 | 18.3% |
| CALL_BUILTIN_CLASS | 250,200 | 12.1% |
| BINARY_OP_ADD_INT | 125,720 | 6.1% |
| LOAD_FAST | 125,440 | 6.1% |


</details>

### BUILD_CONST_KEY_MAP

<details>
<summary> Successors and predecessors for BUILD_CONST_KEY_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 40 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 20 | 50.0% |
| STORE_FAST | 20 | 50.0% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 500,420 | 33.3% |
| STORE_ATTR_SLOT | 500,280 | 33.3% |
| RESUME_CHECK | 250,160 | 16.7% |
| LOAD_FAST | 125,280 | 8.3% |
| POP_TOP | 125,200 | 8.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 750,840 | 50.0% |
| STORE_FAST | 750,740 | 50.0% |
| SWAP | 120 | 0.0% |
| CALL | 40 | 0.0% |
| COMPARE_OP | 40 | 0.0% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 124,140 | 99.9% |
| CALL_INTRINSIC_1 | 100 | 0.1% |
| LOAD_FAST | 40 | 0.0% |
| STORE_ATTR | 20 | 0.0% |
| RESUME | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 124,320 | 100.0% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 626,600 | 27.8% |
| LOAD_FAST_LOAD_FAST | 625,640 | 27.8% |
| LOAD_FAST | 499,700 | 22.2% |
| BUILD_TUPLE | 250,240 | 11.1% |
| CALL_METHOD_DESCRIPTOR_FAST | 125,100 | 5.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 1,251,180 | 55.5% |
| YIELD_VALUE | 626,720 | 27.8% |
| BUILD_TUPLE | 250,240 | 11.1% |
| CALL_BUILTIN_FAST | 124,120 | 5.5% |
| LOAD_CONST | 220 | 0.0% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,379,540 | 57.8% |
| LOAD_FAST | 501,700 | 21.0% |
| LOAD_FAST_LOAD_FAST | 249,460 | 10.4% |
| PUSH_NULL | 125,580 | 5.3% |
| CALL_METHOD_DESCRIPTOR_O | 125,100 | 5.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 1,376,720 | 57.7% |
| STORE_FAST | 751,260 | 31.5% |
| LOAD_FAST | 125,480 | 5.3% |
| RESUME_CHECK | 124,700 | 5.2% |
| CALL | 2,720 | 0.1% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| DICT_MERGE | 140 | 63.6% |
| LOAD_FAST | 80 | 36.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 120 | 54.5% |
| COPY_FREE_VARS | 80 | 36.4% |
| RESUME_CHECK | 20 | 9.1% |


</details>

### CALL_INTRINSIC_1

<details>
<summary> Successors and predecessors for CALL_INTRINSIC_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LIST_EXTEND | 100 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BUILD_MAP | 100 | 100.0% |


</details>

### CALL_KW

<details>
<summary> Successors and predecessors for CALL_KW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 499,700 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 375,280 | 75.1% |
| RETURN_VALUE | 124,180 | 24.9% |
| RESUME | 120 | 0.0% |
| STORE_FAST | 100 | 0.0% |
| LOAD_FAST | 20 | 0.0% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 2,254,360 | 54.9% |
| LOAD_CONST | 974,300 | 23.7% |
| LOAD_FAST_LOAD_FAST | 872,260 | 21.2% |
| COMPARE_OP | 3,480 | 0.1% |
| LOAD_GLOBAL | 260 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 4,004,000 | 97.5% |
| STORE_FAST | 96,720 | 2.4% |
| COMPARE_OP | 3,480 | 0.1% |
| COMPARE_OP_INT | 640 | 0.0% |
| POP_JUMP_IF_TRUE | 200 | 0.0% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 745,800 | 54.4% |
| LOAD_GLOBAL_MODULE | 375,200 | 27.3% |
| LOAD_CONST | 250,260 | 18.2% |
| LOAD_FAST | 320 | 0.0% |
| LOAD_ATTR | 140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,247,660 | 90.9% |
| STORE_FAST | 124,180 | 9.1% |
| POP_JUMP_IF_TRUE | 120 | 0.0% |


</details>

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 500,440 | 57.2% |
| LOAD_CONST | 153,520 | 17.5% |
| LOAD_FAST | 124,380 | 14.2% |
| POP_JUMP_IF_FALSE | 96,800 | 11.1% |
| COMPARE_OP | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 596,720 | 68.2% |
| TO_BOOL_INT | 153,880 | 17.6% |
| LOAD_ATTR_INSTANCE_VALUE | 124,140 | 14.2% |
| TO_BOOL | 240 | 0.0% |
| TO_BOOL_NONE | 120 | 0.0% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 125,220 | 33.5% |
| CALL_PY_EXACT_ARGS | 124,180 | 33.2% |
| LOAD_ATTR_PROPERTY | 124,140 | 33.2% |
| CALL | 80 | 0.0% |
| CALL_FUNCTION_EX | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 373,520 | 100.0% |
| RESUME | 140 | 0.0% |
| RETURN_GENERATOR | 40 | 0.0% |


</details>

### DICT_MERGE

<details>
<summary> Successors and predecessors for DICT_MERGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 140 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 140 | 100.0% |


</details>

### ENTER_EXECUTOR

<details>
<summary> Successors and predecessors for ENTER_EXECUTOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 548,760 | 80.8% |
| POP_TOP | 124,700 | 18.4% |
| CALL_LIST_APPEND | 4,780 | 0.7% |
| POP_JUMP_IF_TRUE | 360 | 0.1% |
| JUMP_BACKWARD | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 424,220 | 62.5% |
| CALL_LIST_APPEND | 129,580 | 19.1% |
| LOAD_CONST | 122,340 | 18.0% |
| BINARY_SUBSCR_GETITEM | 2,480 | 0.4% |
| CALL | 140 | 0.0% |


</details>

### EXTENDED_ARG

<details>
<summary> Successors and predecessors for EXTENDED_ARG </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_LIST | 124,220 | 99.7% |
| POP_JUMP_IF_FALSE | 340 | 0.3% |
| COMPARE_OP_INT | 40 | 0.0% |
| TO_BOOL | 20 | 0.0% |
| COMPARE_OP | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 124,300 | 99.7% |
| JUMP_BACKWARD | 340 | 0.3% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 875,320 | 58.3% |
| GET_ITER | 624,920 | 41.6% |
| FOR_ITER | 1,480 | 0.1% |
| LOAD_FAST | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,000,480 | 66.6% |
| LOAD_FAST_LOAD_FAST | 125,120 | 8.3% |
| LOAD_GLOBAL_BUILTIN | 124,960 | 8.3% |
| UNPACK_SEQUENCE_TWO_TUPLE | 124,960 | 8.3% |
| NOP | 124,200 | 8.3% |


</details>

### IMPORT_FROM

<details>
<summary> Successors and predecessors for IMPORT_FROM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| IMPORT_NAME | 160 | 72.7% |
| STORE_NAME | 60 | 27.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_NAME | 140 | 63.6% |
| STORE_FAST | 80 | 36.4% |


</details>

### IMPORT_NAME

<details>
<summary> Successors and predecessors for IMPORT_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 200 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| IMPORT_FROM | 160 | 80.0% |
| STORE_NAME | 40 | 20.0% |


</details>

### IS_OP

<details>
<summary> Successors and predecessors for IS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 280 | 45.2% |
| LOAD_FAST_LOAD_FAST | 180 | 29.0% |
| LOAD_GLOBAL | 60 | 9.7% |
| LOAD_ATTR | 40 | 6.5% |
| LOAD_ATTR_INSTANCE_VALUE | 40 | 6.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 600 | 96.8% |
| POP_JUMP_IF_TRUE | 20 | 3.2% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 750,180 | 49.8% |
| STORE_FAST_STORE_FAST | 501,600 | 33.3% |
| CALL_LIST_APPEND | 126,540 | 8.4% |
| BINARY_OP_INPLACE_ADD_UNICODE | 124,220 | 8.3% |
| POP_JUMP_IF_FALSE | 800 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 875,320 | 58.1% |
| FOR_ITER_GEN | 626,700 | 41.6% |
| FOR_ITER_RANGE | 1,320 | 0.1% |
| LOAD_GLOBAL_BUILTIN | 700 | 0.0% |
| FOR_ITER_LIST | 420 | 0.0% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 550,320 | 46.9% |
| POP_EXCEPT | 249,160 | 21.2% |
| POP_TOP | 125,140 | 10.7% |
| POP_JUMP_IF_FALSE | 125,000 | 10.6% |
| STORE_ATTR_INSTANCE_VALUE | 124,300 | 10.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 674,160 | 57.4% |
| LOAD_FAST | 500,000 | 42.6% |
| LOAD_GLOBAL_MODULE | 60 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 40 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_FAST | 120 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 120 | 100.0% |


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 100 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 100 | 100.0% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 250,180 | 39.4% |
| LOAD_FAST | 131,240 | 20.6% |
| LOAD_FAST_LOAD_FAST | 125,540 | 19.8% |
| LOAD_GLOBAL_MODULE | 125,280 | 19.7% |
| LOAD_ATTR | 1,600 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 126,860 | 20.0% |
| STORE_FAST | 125,420 | 19.7% |
| PUSH_NULL | 125,400 | 19.7% |
| CALL_PY_EXACT_ARGS | 125,080 | 19.7% |
| CALL_PY_WITH_DEFAULTS | 124,960 | 19.7% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,208,400 | 33.5% |
| LOAD_ATTR_METHOD_NO_DICT | 3,870,620 | 18.0% |
| LOAD_CONST | 2,256,440 | 10.5% |
| STORE_FAST | 1,376,620 | 6.4% |
| LOAD_FAST_LOAD_FAST | 1,301,160 | 6.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 2,491,840 | 11.6% |
| LOAD_CONST | 2,256,440 | 10.5% |
| LOAD_FAST | 1,754,500 | 8.2% |
| COMPARE_OP_INT | 1,751,620 | 8.1% |
| STORE_FAST | 1,723,460 | 8.0% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 372,620 | 20.0% |
| LOAD_FAST | 372,520 | 20.0% |
| RESUME_CHECK | 248,780 | 13.4% |
| LOAD_GLOBAL_MODULE | 248,280 | 13.3% |
| STORE_FAST | 246,840 | 13.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,241,800 | 66.7% |
| STORE_ATTR_INSTANCE_VALUE | 248,280 | 13.3% |
| LOAD_ATTR_METHOD_WITH_VALUES | 246,640 | 13.2% |
| BINARY_OP_ADD_UNICODE | 124,120 | 6.7% |
| LOAD_ATTR | 600 | 0.0% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 7,926,960 | 15.1% |
| STORE_FAST | 7,130,300 | 13.5% |
| RESUME_CHECK | 6,407,520 | 12.2% |
| LOAD_GLOBAL_BUILTIN | 3,999,820 | 7.6% |
| LOAD_ATTR_INSTANCE_VALUE | 2,415,000 | 4.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 7,208,400 | 13.7% |
| LOAD_ATTR_INSTANCE_VALUE | 5,955,360 | 11.3% |
| LOAD_ATTR_METHOD_NO_DICT | 4,500,380 | 8.5% |
| LOAD_ATTR_SLOT | 4,479,500 | 8.5% |
| STORE_ATTR_SLOT | 4,127,360 | 7.8% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 120 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 120 | 100.0% |


</details>

### LOAD_FAST_CHECK

<details>
<summary> Successors and predecessors for LOAD_FAST_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 80 | 44.4% |
| LOAD_FAST_LOAD_FAST | 60 | 33.3% |
| LOAD_FAST | 20 | 11.1% |
| LOAD_ATTR_METHOD_NO_DICT | 20 | 11.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_NOT_NONE | 80 | 44.4% |
| BUILD_TUPLE | 60 | 33.3% |
| LOAD_FAST | 20 | 11.1% |
| CALL_LIST_APPEND | 20 | 11.1% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,301,460 | 17.1% |
| POP_JUMP_IF_FALSE | 947,500 | 12.5% |
| JUMP_FORWARD | 674,160 | 8.9% |
| POP_JUMP_IF_NONE | 626,600 | 8.2% |
| STORE_ATTR_SLOT | 625,320 | 8.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,301,160 | 17.1% |
| STORE_ATTR_SLOT | 1,125,140 | 14.8% |
| COMPARE_OP | 872,260 | 11.5% |
| COMPARE_OP_INT | 675,000 | 8.9% |
| BUILD_TUPLE | 625,640 | 8.2% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,280 | 21.8% |
| STORE_FAST | 900 | 15.3% |
| POP_JUMP_IF_FALSE | 620 | 10.5% |
| RESUME | 540 | 9.2% |
| RESUME_CHECK | 320 | 5.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,460 | 24.8% |
| LOAD_GLOBAL_MODULE | 1,240 | 21.1% |
| LOAD_GLOBAL_BUILTIN | 1,220 | 20.7% |
| LOAD_ATTR | 440 | 7.5% |
| CALL | 340 | 5.8% |


</details>

### LOAD_NAME

<details>
<summary> Successors and predecessors for LOAD_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 80 | 36.4% |
| RESUME | 60 | 27.3% |
| STORE_NAME | 40 | 18.2% |
| MAKE_FUNCTION | 20 | 9.1% |
| LOAD_NAME | 20 | 9.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_NAME | 80 | 36.4% |
| CALL | 60 | 27.3% |
| BUILD_TUPLE | 40 | 18.2% |
| LOAD_CONST | 20 | 9.1% |
| LOAD_NAME | 20 | 9.1% |


</details>

### LOAD_SUPER_ATTR

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 20 | 33.3% |
| LOAD_FAST_LOAD_FAST | 20 | 33.3% |
| LOAD_SUPER_ATTR_METHOD | 20 | 33.3% |


</details>

### MAKE_CELL

<details>
<summary> Successors and predecessors for MAKE_CELL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 124,660 | 99.9% |
| CALL | 80 | 0.1% |
| CALL_PY_EXACT_ARGS | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 124,720 | 100.0% |
| RESUME | 60 | 0.0% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP | 4,004,000 | 31.9% |
| TO_BOOL_BOOL | 3,869,000 | 30.8% |
| COMPARE_OP_INT | 1,800,240 | 14.3% |
| CONTAINS_OP | 1,247,660 | 9.9% |
| TO_BOOL | 627,380 | 5.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,926,960 | 63.2% |
| LOAD_FAST_LOAD_FAST | 947,500 | 7.6% |
| LOAD_GLOBAL_MODULE | 872,880 | 7.0% |
| POP_TOP | 748,740 | 6.0% |
| ENTER_EXECUTOR | 548,760 | 4.4% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,375,620 | 50.1% |
| LOAD_ATTR_SLOT | 870,080 | 31.7% |
| LOAD_ATTR_INSTANCE_VALUE | 372,500 | 13.6% |
| CALL_BUILTIN_FAST | 125,100 | 4.6% |
| LOAD_ATTR | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,743,300 | 63.5% |
| LOAD_FAST_LOAD_FAST | 626,600 | 22.8% |
| LOAD_GLOBAL_BUILTIN | 373,360 | 13.6% |
| LOAD_GLOBAL_MODULE | 120 | 0.0% |
| LOAD_GLOBAL | 100 | 0.0% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 874,000 | 63.6% |
| LOAD_ATTR_INSTANCE_VALUE | 499,680 | 36.4% |
| CALL_BUILTIN_FAST | 120 | 0.0% |
| LOAD_ATTR | 80 | 0.0% |
| LOAD_FAST_CHECK | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 999,500 | 72.7% |
| LOAD_GLOBAL_MODULE | 125,220 | 9.1% |
| RETURN_CONST | 124,180 | 9.0% |
| LOAD_GLOBAL_BUILTIN | 124,160 | 9.0% |
| JUMP_BACKWARD | 340 | 0.0% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 750,920 | 40.0% |
| TO_BOOL_BOOL | 596,160 | 31.8% |
| TO_BOOL | 373,760 | 19.9% |
| TO_BOOL_INT | 155,500 | 8.3% |
| COMPARE_OP | 200 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 748,900 | 39.9% |
| LOAD_FAST_LOAD_FAST | 250,720 | 13.4% |
| NOP | 250,360 | 13.3% |
| LOAD_GLOBAL_BUILTIN | 249,800 | 13.3% |
| STORE_FAST | 153,520 | 8.2% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 750,520 | 42.9% |
| POP_TOP | 374,860 | 21.4% |
| STORE_ATTR_INSTANCE_VALUE | 248,500 | 14.2% |
| POP_JUMP_IF_FALSE | 125,840 | 7.2% |
| POP_EXCEPT | 124,180 | 7.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 626,060 | 35.8% |
| INTERPRETER_EXIT | 500,800 | 28.6% |
| STORE_FAST | 248,460 | 14.2% |
| END_FOR | 125,120 | 7.2% |
| EXIT_INIT_CHECK | 124,280 | 7.1% |


</details>

### SET_FUNCTION_ATTRIBUTE

<details>
<summary> Successors and predecessors for SET_FUNCTION_ATTRIBUTE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_FUNCTION | 240 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 80 | 33.3% |
| STORE_NAME | 60 | 25.0% |
| LOAD_DEREF | 40 | 16.7% |
| LOAD_GLOBAL_MODULE | 40 | 16.7% |
| STORE_FAST | 20 | 8.3% |


</details>

### STORE_ATTR

<details>
<summary> Successors and predecessors for STORE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,980 | 60.6% |
| LOAD_FAST_LOAD_FAST | 1,500 | 30.5% |
| LOAD_DEREF | 280 | 5.7% |
| SWAP | 80 | 1.6% |
| LOAD_ATTR | 40 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 1,160 | 23.6% |
| LOAD_FAST | 1,020 | 20.7% |
| STORE_ATTR_INSTANCE_VALUE | 860 | 17.5% |
| LOAD_FAST_LOAD_FAST | 480 | 9.8% |
| LOAD_CONST | 440 | 8.9% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,723,460 | 11.4% |
| RETURN_VALUE | 1,674,120 | 11.1% |
| LOAD_FAST | 1,250,300 | 8.3% |
| BINARY_OP_ADD_INT | 1,153,020 | 7.6% |
| BINARY_OP | 1,050,900 | 7.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,130,300 | 47.2% |
| LOAD_CONST | 1,376,620 | 9.1% |
| LOAD_FAST_LOAD_FAST | 1,301,460 | 8.6% |
| LOAD_GLOBAL_BUILTIN | 1,251,200 | 8.3% |
| LOAD_GLOBAL_MODULE | 1,124,820 | 7.4% |


</details>

### STORE_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_TUPLE | 120 | 85.7% |
| UNPACK_SEQUENCE | 20 | 14.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_STR | 120 | 85.7% |
| STORE_ATTR | 20 | 14.3% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 1,751,600 | 70.0% |
| UNPACK_SEQUENCE_LIST | 751,800 | 30.0% |
| UNPACK_SEQUENCE | 380 | 0.0% |
| UNPACK_SEQUENCE_TUPLE | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,251,420 | 50.0% |
| JUMP_BACKWARD | 501,600 | 20.0% |
| LOAD_FAST_LOAD_FAST | 375,300 | 15.0% |
| LOAD_GLOBAL_BUILTIN | 250,220 | 10.0% |
| LOAD_GLOBAL_MODULE | 125,080 | 5.0% |


</details>

### STORE_NAME

<details>
<summary> Successors and predecessors for STORE_NAME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_FUNCTION | 240 | 28.6% |
| LOAD_CONST | 200 | 23.8% |
| IMPORT_FROM | 140 | 16.7% |
| LOAD_NAME | 80 | 9.5% |
| CALL | 60 | 7.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 520 | 61.9% |
| POP_TOP | 80 | 9.5% |
| RETURN_CONST | 80 | 9.5% |
| LOAD_BUILD_CLASS | 60 | 7.1% |
| IMPORT_FROM | 60 | 7.1% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 125,180 | 50.1% |
| BINARY_OP_ADD_INT | 124,180 | 49.7% |
| BUILD_LIST | 120 | 0.0% |
| ENTER_EXECUTOR | 120 | 0.0% |
| LOAD_FAST_AND_CLEAR | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 125,180 | 50.1% |
| STORE_ATTR_INSTANCE_VALUE | 124,140 | 49.7% |
| BUILD_LIST | 120 | 0.0% |
| STORE_FAST | 120 | 0.0% |
| FOR_ITER_TUPLE | 120 | 0.0% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 480 | 47.1% |
| LOAD_FAST | 160 | 15.7% |
| CALL | 120 | 11.8% |
| FOR_ITER | 100 | 9.8% |
| STORE_ATTR | 40 | 3.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 380 | 37.3% |
| UNPACK_SEQUENCE_TWO_TUPLE | 340 | 33.3% |
| LOAD_FAST | 120 | 11.8% |
| UNPACK_SEQUENCE_TUPLE | 80 | 7.8% |
| STORE_FAST | 40 | 3.9% |


</details>

### YIELD_VALUE

<details>
<summary> Successors and predecessors for YIELD_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 626,720 | 100.0% |
| CALL | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 626,680 | 100.0% |
| INTERPRETER_EXIT | 60 | 0.0% |
| UNPACK_SEQUENCE | 20 | 0.0% |


</details>

### RESUME

<details>
<summary> Successors and predecessors for RESUME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 1,080 | 55.1% |
| CACHE | 500 | 25.5% |
| COPY_FREE_VARS | 140 | 7.1% |
| CALL_KW | 120 | 6.1% |
| MAKE_CELL | 60 | 3.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 760 | 38.8% |
| LOAD_GLOBAL | 540 | 27.6% |
| LOAD_FAST_LOAD_FAST | 180 | 9.2% |
| LOAD_CONST | 140 | 7.1% |
| NOP | 120 | 6.1% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,528,180 | 54.0% |
| BINARY_OP_MULTIPLY_INT | 925,280 | 32.7% |
| LOAD_FAST_LOAD_FAST | 126,200 | 4.5% |
| BINARY_OP | 125,720 | 4.4% |
| CALL_LEN | 124,980 | 4.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,153,020 | 40.7% |
| BINARY_SLICE | 801,280 | 28.3% |
| LOAD_CONST | 376,000 | 13.3% |
| BINARY_OP_MULTIPLY_INT | 250,200 | 8.8% |
| BINARY_OP | 125,540 | 4.4% |


</details>

### BINARY_OP_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 124,220 | 50.0% |
| LOAD_DEREF | 124,120 | 49.9% |
| LOAD_FAST_LOAD_FAST | 100 | 0.0% |
| BINARY_SUBSCR_LIST_INT | 40 | 0.0% |
| BINARY_OP | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_INPLACE_ADD_UNICODE | 124,220 | 50.0% |
| CALL_BUILTIN_FAST | 124,120 | 49.9% |
| LOAD_FAST | 80 | 0.0% |
| CALL | 40 | 0.0% |
| STORE_FAST | 40 | 0.0% |


</details>

### BINARY_OP_MULTIPLY_INT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,300,780 | 83.9% |
| BINARY_OP_ADD_INT | 250,200 | 16.1% |
| BINARY_OP | 200 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 925,280 | 59.7% |
| LOAD_FAST | 500,440 | 32.3% |
| LOAD_CONST | 124,980 | 8.1% |
| BINARY_OP | 480 | 0.0% |


</details>

### BINARY_OP_SUBTRACT_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 40 | 66.7% |
| BINARY_OP | 20 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 60 | 100.0% |


</details>

### BINARY_OP_SUBTRACT_INT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 321,840 | 100.0% |
| BINARY_OP | 60 | 0.0% |
| LOAD_FAST_LOAD_FAST | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 197,380 | 61.3% |
| BINARY_SUBSCR_LIST_INT | 124,520 | 38.7% |
| BINARY_SUBSCR | 20 | 0.0% |


</details>

### BINARY_SUBSCR_DICT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 125,140 | 50.2% |
| LOAD_FAST | 124,220 | 49.8% |
| BINARY_SUBSCR | 40 | 0.0% |
| LOAD_CONST | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_EXC_INFO | 249,160 | 99.9% |
| STORE_FAST | 240 | 0.1% |
| LOAD_FAST | 20 | 0.0% |
| CALL_BUILTIN_CLASS | 20 | 0.0% |


</details>

### BINARY_SUBSCR_GETITEM

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_GETITEM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 247,740 | 99.0% |
| ENTER_EXECUTOR | 2,480 | 1.0% |
| BINARY_SUBSCR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 250,260 | 100.0% |


</details>

### BINARY_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 249,980 | 50.0% |
| LOAD_FAST | 125,080 | 25.0% |
| BINARY_OP_SUBTRACT_INT | 124,520 | 24.9% |
| BINARY_SUBSCR | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 250,000 | 50.0% |
| STORE_FAST | 249,640 | 50.0% |
| BINARY_OP_ADD_UNICODE | 40 | 0.0% |


</details>

### BINARY_SUBSCR_TUPLE_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_TUPLE_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 125,460 | 100.0% |
| BINARY_SUBSCR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 125,160 | 99.7% |
| CALL_LIST_APPEND | 300 | 0.2% |
| RETURN_VALUE | 20 | 0.0% |
| CALL | 20 | 0.0% |


</details>

### CALL_ALLOC_AND_ENTER_INIT

<details>
<summary> Successors and predecessors for CALL_ALLOC_AND_ENTER_INIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 124,180 | 99.9% |
| CALL | 40 | 0.0% |
| LOAD_FAST_LOAD_FAST | 40 | 0.0% |
| ENTER_EXECUTOR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 124,280 | 100.0% |


</details>

### CALL_BOUND_METHOD_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_BOUND_METHOD_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 549,520 | 100.0% |
| LOAD_CONST | 80 | 0.0% |
| CALL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 549,540 | 100.0% |
| POP_TOP | 80 | 0.0% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 623,680 | 45.4% |
| BINARY_SLICE | 375,160 | 27.3% |
| BINARY_OP | 250,200 | 18.2% |
| LOAD_GLOBAL_BUILTIN | 124,240 | 9.0% |
| LOAD_CONST | 320 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 750,680 | 54.6% |
| GET_ITER | 374,640 | 27.3% |
| LOAD_FAST | 124,380 | 9.1% |
| RETURN_VALUE | 124,140 | 9.0% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 80 | 0.0% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 250,620 | 33.5% |
| LOAD_FAST | 125,280 | 16.7% |
| LOAD_ATTR_INSTANCE_VALUE | 124,520 | 16.6% |
| BUILD_TUPLE | 124,120 | 16.6% |
| BINARY_OP_ADD_UNICODE | 124,120 | 16.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 374,880 | 50.1% |
| POP_JUMP_IF_NONE | 125,100 | 16.7% |
| POP_TOP | 124,200 | 16.6% |
| RETURN_VALUE | 124,200 | 16.6% |
| LOAD_CONST | 320 | 0.0% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 249,460 | 50.0% |
| PUSH_NULL | 124,960 | 25.1% |
| LOAD_CONST | 124,220 | 24.9% |
| CALL_BUILTIN_CLASS | 80 | 0.0% |
| CALL | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 249,240 | 50.0% |
| LOAD_CONST | 125,100 | 25.1% |
| PUSH_EXC_INFO | 124,180 | 24.9% |
| RETURN_VALUE | 260 | 0.1% |
| BEFORE_WITH | 20 | 0.0% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 500,440 | 57.1% |
| BINARY_SLICE | 251,300 | 28.7% |
| LOAD_ATTR_INSTANCE_VALUE | 124,120 | 14.2% |
| CALL | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 376,300 | 43.0% |
| RETURN_VALUE | 250,220 | 28.6% |
| CALL_LIST_APPEND | 125,340 | 14.3% |
| UNPACK_SEQUENCE_TWO_TUPLE | 124,120 | 14.2% |
| CALL | 20 | 0.0% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 374,600 | 74.9% |
| LOAD_GLOBAL_MODULE | 125,100 | 25.0% |
| CALL | 180 | 0.0% |
| BUILD_TUPLE | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 499,720 | 100.0% |
| TO_BOOL | 180 | 0.0% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,375,620 | 91.7% |
| LOAD_ATTR_INSTANCE_VALUE | 124,100 | 8.3% |
| CALL | 260 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,000,840 | 66.7% |
| STORE_FAST | 250,000 | 16.7% |
| BINARY_OP_ADD_INT | 124,980 | 8.3% |
| LOAD_GLOBAL_MODULE | 124,040 | 8.3% |
| BINARY_OP | 40 | 0.0% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 376,120 | 59.5% |
| ENTER_EXECUTOR | 129,580 | 20.5% |
| CALL_BUILTIN_O | 125,340 | 19.8% |
| BINARY_SLICE | 320 | 0.1% |
| BINARY_SUBSCR_TUPLE_INT | 300 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 250,140 | 39.6% |
| LOAD_FAST | 250,000 | 39.6% |
| JUMP_BACKWARD | 126,540 | 20.0% |
| ENTER_EXECUTOR | 4,780 | 0.8% |
| JUMP_FORWARD | 180 | 0.0% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 125,100 | 25.0% |
| LOAD_ATTR_METHOD_LAZY_DICT | 125,080 | 25.0% |
| LOAD_FAST | 124,980 | 25.0% |
| LOAD_ATTR_MODULE | 124,160 | 24.8% |
| LOAD_GLOBAL_MODULE | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 125,100 | 25.0% |
| BUILD_TUPLE | 125,100 | 25.0% |
| POP_TOP | 125,020 | 25.0% |
| STORE_FAST | 124,260 | 24.9% |
| LIST_APPEND | 120 | 0.0% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,491,840 | 100.0% |
| CALL | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 1,740,120 | 69.8% |
| UNPACK_SEQUENCE_LIST | 751,760 | 30.2% |
| UNPACK_SEQUENCE | 40 | 0.0% |


</details>

### CALL_METHOD_DESCRIPTOR_NOARGS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_NOARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 249,200 | 66.6% |
| LOAD_ATTR_METHOD_LAZY_DICT | 125,080 | 33.4% |
| CALL | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 125,100 | 33.4% |
| RETURN_VALUE | 125,100 | 33.4% |
| STORE_FAST | 124,140 | 33.2% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 622,480 | 71.5% |
| RETURN_VALUE | 248,240 | 28.5% |
| CALL | 180 | 0.0% |
| LOAD_CONST | 120 | 0.0% |
| STORE_FAST | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 620,640 | 71.2% |
| BUILD_TUPLE | 125,100 | 14.4% |
| CALL | 125,100 | 14.4% |
| RETURN_VALUE | 120 | 0.0% |
| STORE_FAST | 120 | 0.0% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,247,480 | 53.1% |
| LOAD_ATTR_METHOD_NO_DICT | 1,865,040 | 30.5% |
| LOAD_ATTR_METHOD_WITH_VALUES | 497,500 | 8.1% |
| LOAD_FAST_LOAD_FAST | 249,300 | 4.1% |
| LOAD_ATTR | 125,080 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 5,861,300 | 95.9% |
| RETURN_GENERATOR | 125,100 | 2.0% |
| COPY_FREE_VARS | 124,180 | 2.0% |
| MAKE_CELL | 40 | 0.0% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 125,080 | 33.4% |
| LOAD_ATTR | 124,960 | 33.4% |
| LOAD_CONST | 124,120 | 33.2% |
| CALL | 60 | 0.0% |
| LOAD_FAST_LOAD_FAST | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 374,240 | 100.0% |


</details>

### CALL_STR_1

<details>
<summary> Successors and predecessors for CALL_STR_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 40 | 66.7% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 20 | 33.3% |


</details>

### CALL_TUPLE_1

<details>
<summary> Successors and predecessors for CALL_TUPLE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 20 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 20 | 100.0% |


</details>

### CALL_TYPE_1

<details>
<summary> Successors and predecessors for CALL_TYPE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 20 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 20 | 100.0% |


</details>

### COMPARE_OP_FLOAT

<details>
<summary> Successors and predecessors for COMPARE_OP_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 20 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 20 | 100.0% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,751,620 | 57.4% |
| LOAD_FAST_LOAD_FAST | 675,000 | 22.1% |
| LOAD_GLOBAL_MODULE | 373,920 | 12.3% |
| LOAD_ATTR_INSTANCE_VALUE | 125,000 | 4.1% |
| LOAD_ATTR_SLOT | 124,960 | 4.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,800,240 | 59.0% |
| POP_JUMP_IF_TRUE | 750,920 | 24.6% |
| COPY | 500,440 | 16.4% |
| EXTENDED_ARG | 40 | 0.0% |
| RETURN_VALUE | 20 | 0.0% |


</details>

### COMPARE_OP_STR

<details>
<summary> Successors and predecessors for COMPARE_OP_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 60 | 42.9% |
| LOAD_GLOBAL_MODULE | 40 | 28.6% |
| COMPARE_OP | 20 | 14.3% |
| LOAD_FAST | 20 | 14.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 140 | 100.0% |


</details>

### FOR_ITER_GEN

<details>
<summary> Successors and predecessors for FOR_ITER_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 626,700 | 83.4% |
| GET_ITER | 125,100 | 16.6% |
| FOR_ITER | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 626,680 | 83.4% |
| POP_TOP | 125,100 | 16.6% |
| RESUME | 40 | 0.0% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 124,240 | 99.6% |
| JUMP_BACKWARD | 420 | 0.3% |
| FOR_ITER | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 122,700 | 98.4% |
| LOAD_CONST | 1,920 | 1.5% |
| LOAD_FAST | 60 | 0.0% |
| BUILD_LIST | 20 | 0.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 20 | 0.0% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 1,320 | 75.9% |
| GET_ITER | 360 | 20.7% |
| FOR_ITER | 60 | 3.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,480 | 85.1% |
| LOAD_FAST | 160 | 9.2% |
| LOAD_CONST | 100 | 5.7% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 120 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_LOAD_FAST | 120 | 100.0% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,955,360 | 78.7% |
| LOAD_DEREF | 1,241,800 | 16.4% |
| LOAD_FAST_LOAD_FAST | 249,140 | 3.3% |
| COPY | 124,140 | 1.6% |
| LOAD_ATTR | 1,520 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,415,000 | 31.9% |
| LOAD_ATTR_METHOD_NO_DICT | 869,840 | 11.5% |
| CONTAINS_OP | 745,800 | 9.8% |
| LOAD_FAST_LOAD_FAST | 549,760 | 7.3% |
| POP_JUMP_IF_NOT_NONE | 499,680 | 6.6% |


</details>

### LOAD_ATTR_METHOD_LAZY_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_LAZY_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 250,160 | 100.0% |
| LOAD_ATTR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_FAST | 125,080 | 50.0% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 125,080 | 50.0% |
| CALL | 40 | 0.0% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,500,380 | 53.9% |
| RETURN_VALUE | 1,740,080 | 20.8% |
| LOAD_ATTR_SLOT | 870,040 | 10.4% |
| LOAD_ATTR_INSTANCE_VALUE | 869,840 | 10.4% |
| LOAD_CONST | 250,240 | 3.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,870,620 | 46.3% |
| LOAD_FAST | 1,996,120 | 23.9% |
| CALL_PY_EXACT_ARGS | 1,865,040 | 22.3% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 249,200 | 3.0% |
| LOAD_FAST_LOAD_FAST | 125,500 | 1.5% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,246,300 | 62.5% |
| RETURN_VALUE | 499,360 | 25.1% |
| LOAD_DEREF | 246,640 | 12.4% |
| LOAD_ATTR | 440 | 0.0% |
| LOAD_ATTR_INSTANCE_VALUE | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,121,680 | 56.3% |
| CALL_PY_EXACT_ARGS | 497,500 | 25.0% |
| LOAD_FAST_LOAD_FAST | 249,320 | 12.5% |
| LOAD_CONST | 124,140 | 6.2% |
| CALL | 80 | 0.0% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,121,880 | 81.9% |
| LOAD_ATTR_MODULE | 248,320 | 18.1% |
| LOAD_ATTR | 160 | 0.0% |
| LOAD_FAST | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 748,360 | 54.6% |
| LOAD_ATTR_MODULE | 248,320 | 18.1% |
| LOAD_FAST | 124,380 | 9.1% |
| LOAD_FAST_LOAD_FAST | 124,200 | 9.1% |
| CALL_METHOD_DESCRIPTOR_FAST | 124,160 | 9.1% |


</details>

### LOAD_ATTR_PROPERTY

<details>
<summary> Successors and predecessors for LOAD_ATTR_PROPERTY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,493,360 | 100.0% |
| LOAD_ATTR | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,369,460 | 91.7% |
| COPY_FREE_VARS | 124,140 | 8.3% |


</details>

### LOAD_ATTR_SLOT

<details>
<summary> Successors and predecessors for LOAD_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,479,500 | 97.3% |
| LOAD_FAST_LOAD_FAST | 124,960 | 2.7% |
| LOAD_ATTR | 440 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 1,119,280 | 24.3% |
| POP_JUMP_IF_NONE | 870,080 | 18.9% |
| LOAD_ATTR_METHOD_NO_DICT | 870,040 | 18.9% |
| TO_BOOL_BOOL | 870,040 | 18.9% |
| STORE_FAST | 250,280 | 5.4% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,251,200 | 23.8% |
| RESUME_CHECK | 1,124,240 | 21.4% |
| LOAD_FAST | 499,600 | 9.5% |
| POP_JUMP_IF_NONE | 373,360 | 7.1% |
| PUSH_EXC_INFO | 373,280 | 7.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,999,820 | 76.2% |
| CALL_ISINSTANCE | 374,600 | 7.1% |
| LOAD_GLOBAL_MODULE | 373,480 | 7.1% |
| CHECK_EXC_MATCH | 373,320 | 7.1% |
| CALL_BUILTIN_CLASS | 124,240 | 2.4% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,879,700 | 39.7% |
| STORE_FAST | 1,124,820 | 15.5% |
| POP_JUMP_IF_FALSE | 872,880 | 12.0% |
| RESUME_CHECK | 749,480 | 10.3% |
| LOAD_GLOBAL_BUILTIN | 373,480 | 5.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP | 2,254,360 | 31.1% |
| LOAD_FAST | 1,875,220 | 25.9% |
| LOAD_ATTR_MODULE | 1,121,880 | 15.5% |
| LOAD_FAST_LOAD_FAST | 375,320 | 5.2% |
| CONTAINS_OP | 375,200 | 5.2% |


</details>

### LOAD_SUPER_ATTR_METHOD

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_METHOD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 125,120 | 100.0% |
| LOAD_SUPER_ATTR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 125,080 | 100.0% |
| LOAD_FAST_LOAD_FAST | 40 | 0.0% |
| CALL | 20 | 0.0% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 5,861,300 | 54.4% |
| LOAD_ATTR_PROPERTY | 1,369,460 | 12.7% |
| FOR_ITER_GEN | 626,680 | 5.8% |
| CALL_BOUND_METHOD_EXACT_ARGS | 549,540 | 5.1% |
| CACHE | 499,320 | 4.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,407,520 | 59.4% |
| LOAD_GLOBAL_BUILTIN | 1,124,240 | 10.4% |
| LOAD_GLOBAL_MODULE | 749,480 | 7.0% |
| POP_TOP | 626,720 | 5.8% |
| NOP | 622,180 | 5.8% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 621,580 | 45.4% |
| LOAD_FAST_LOAD_FAST | 373,320 | 27.3% |
| LOAD_DEREF | 248,280 | 18.1% |
| SWAP | 124,140 | 9.1% |
| STORE_ATTR | 860 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 497,180 | 36.3% |
| RETURN_CONST | 248,500 | 18.2% |
| LOAD_FAST_LOAD_FAST | 124,680 | 9.1% |
| LOAD_GLOBAL_BUILTIN | 124,340 | 9.1% |
| JUMP_FORWARD | 124,300 | 9.1% |


</details>

### STORE_ATTR_SLOT

<details>
<summary> Successors and predecessors for STORE_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,127,360 | 78.6% |
| LOAD_FAST_LOAD_FAST | 1,125,140 | 21.4% |
| STORE_ATTR | 1,160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,876,460 | 35.7% |
| LOAD_CONST | 1,000,640 | 19.0% |
| RETURN_CONST | 750,520 | 14.3% |
| LOAD_FAST_LOAD_FAST | 625,320 | 11.9% |
| BUILD_LIST | 500,280 | 9.5% |


</details>

### STORE_SUBSCR_DICT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60 | 33.3% |
| STORE_SUBSCR | 40 | 22.2% |
| LOAD_CONST | 40 | 22.2% |
| LOAD_ATTR_INSTANCE_VALUE | 40 | 22.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 80 | 44.4% |
| JUMP_FORWARD | 40 | 22.2% |
| LOAD_GLOBAL_MODULE | 40 | 22.2% |
| NOP | 20 | 11.1% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 1,376,720 | 30.8% |
| LOAD_FAST | 872,520 | 19.5% |
| LOAD_ATTR_SLOT | 870,040 | 19.5% |
| COPY | 596,720 | 13.4% |
| CALL_ISINSTANCE | 499,720 | 11.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 3,869,000 | 86.6% |
| POP_JUMP_IF_TRUE | 596,160 | 13.3% |
| TO_BOOL_INT | 560 | 0.0% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 377,140 | 70.9% |
| COPY | 153,880 | 28.9% |
| TO_BOOL_BOOL | 560 | 0.1% |
| TO_BOOL | 160 | 0.0% |
| CALL_BUILTIN_O | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 375,720 | 70.7% |
| POP_JUMP_IF_TRUE | 155,500 | 29.2% |
| TO_BOOL_BOOL | 560 | 0.1% |


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 124,200 | 100.0% |
| TO_BOOL | 20 | 0.0% |
| LOAD_FAST | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| EXTENDED_ARG | 124,220 | 100.0% |
| POP_JUMP_IF_TRUE | 20 | 0.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY | 120 | 50.0% |
| TO_BOOL | 60 | 25.0% |
| LOAD_FAST | 60 | 25.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 120 | 50.0% |
| POP_JUMP_IF_TRUE | 120 | 50.0% |


</details>

### TO_BOOL_STR

<details>
<summary> Successors and predecessors for TO_BOOL_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 124,300 | 99.9% |
| STORE_FAST_LOAD_FAST | 120 | 0.1% |
| COPY | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 124,420 | 100.0% |
| POP_JUMP_IF_TRUE | 20 | 0.0% |


</details>

### UNPACK_SEQUENCE_LIST

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 751,760 | 100.0% |
| UNPACK_SEQUENCE | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 751,800 | 100.0% |


</details>

### UNPACK_SEQUENCE_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 250,160 | 66.6% |
| RETURN_VALUE | 125,080 | 33.3% |
| UNPACK_SEQUENCE | 80 | 0.0% |
| CALL_METHOD_DESCRIPTOR_O | 40 | 0.0% |
| FOR_ITER | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 375,300 | 100.0% |
| STORE_FAST_STORE_FAST | 80 | 0.0% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 875,480 | 43.7% |
| YIELD_VALUE | 626,680 | 31.3% |
| STORE_ATTR_SLOT | 250,160 | 12.5% |
| FOR_ITER | 124,960 | 6.2% |
| CALL_BUILTIN_O | 124,120 | 6.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 1,751,600 | 87.5% |
| LOAD_FAST | 250,200 | 12.5% |


</details>


</details>

## Specialization stats

<details>
<summary> specialization stats by family </summary>

### BINARY_OP

<details>
<summary> specialization stats for BINARY_OP family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 2,057,000 | 28.8% |
|          hit | 5,076,780 | 71.1% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 980 | 22.8% |
| Failure | 3,320 | 77.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| and int | 1,560 | 47.0% |
| lshift | 560 | 16.9% |
| floor divide | 320 | 9.6% |
| remainder | 260 | 7.8% |
| true divide other | 260 | 7.8% |
| rshift | 220 | 6.6% |
| or | 140 | 4.2% |


</details>

### BINARY_OP_INPLACE_ADD_UNICODE

<details>
<summary> specialization stats for BINARY_OP_INPLACE_ADD_UNICODE family </summary>


</details>

### BINARY_SLICE

<details>
<summary> specialization stats for BINARY_SLICE family </summary>


</details>

### BINARY_SUBSCR

<details>
<summary> specialization stats for BINARY_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 500,820 | 30.8% |
|          hit | 1,124,880 | 69.2% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 220 | 28.2% |
| Failure | 560 | 71.8% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| out of range | 300 | 53.6% |
| buffer int | 260 | 46.4% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 2,382,140 | 11.6% |
|          hit | 18,074,760 | 88.3% |
|         miss | 220 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 2,660 | 50.2% |
| Failure | 2,640 | 49.8% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| meth descr varargs | 1,200 | 45.5% |
| no dict | 660 | 25.0% |
| class no vectorcall | 260 | 9.8% |
| code complex parameters | 220 | 8.3% |
| meth descr method fastcall keywords | 220 | 8.3% |
| cfunc noargs | 60 | 2.3% |
| other | 20 | 0.8% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 4,100,980 | 57.3% |
|          hit | 3,051,840 | 42.6% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 660 | 15.9% |
| Failure | 3,480 | 84.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| bytes | 2,460 | 70.7% |
| different types | 1,020 | 29.3% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 1,500,140 | 63.0% |
|          hit | 878,400 | 36.9% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 140 | 8.6% |
| Failure | 1,480 | 91.4% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| other | 340 | 23.0% |
| enumerate | 260 | 17.6% |
| dict values | 220 | 14.9% |
| reversed list | 220 | 14.9% |
| callable | 220 | 14.9% |
| map | 160 | 10.8% |
| itertools | 40 | 2.7% |
| set | 20 | 1.4% |


</details>

### LOAD_ATTR

<details>
<summary> specialization stats for LOAD_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 630,920 | 2.4% |
|          hit | 25,640,420 | 97.6% |
|         miss | 140 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 3,580 | 75.8% |
| Failure | 1,140 | 24.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| method | 480 | 42.1% |
| non overriding descriptor | 220 | 19.3% |
| non object slot | 220 | 19.3% |
| not managed dict | 220 | 19.3% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 3,360 | 0.0% |
|          hit | 12,497,840 | 99.9% |
|         miss | 440 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 2,520 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### LOAD_SUPER_ATTR

<details>
<summary> specialization stats for LOAD_SUPER_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 40 | 0.0% |
|          hit | 125,140 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> specialization stats for POP_JUMP_IF_FALSE family </summary>


</details>

### POP_JUMP_IF_NONE

<details>
<summary> specialization stats for POP_JUMP_IF_NONE family </summary>


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> specialization stats for POP_JUMP_IF_NOT_NONE family </summary>


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> specialization stats for POP_JUMP_IF_TRUE family </summary>


</details>

### STORE_ATTR

<details>
<summary> specialization stats for STORE_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 2,900 | 0.0% |
|          hit | 6,621,840 | 99.9% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 2,020 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### STORE_SUBSCR

<details>
<summary> specialization stats for STORE_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 120 | 33.3% |
|          hit | 180 | 50.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 40 | 66.7% |
| Failure | 20 | 33.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| py simple | 20 | 100.0% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 1,000,040 | 16.0% |
|          hit | 5,186,620 | 83.0% |
|         miss | 59,800 | 1.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,900 | 61.3% |
| Failure | 1,200 | 38.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| bytes | 840 | 70.0% |
| sequence | 220 | 18.3% |
| tuple | 140 | 11.7% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 560 | 0.0% |
|          hit | 3,128,980 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 460 | 100.0% |
| Failure | 0 | 0.0% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 133,925,920 | 51.7% |
| Not specialized | 33,303,320 | 12.9% |
| Specialized hits | 91,512,380 | 35.4% |
| Specialized misses | 60,600 | 0.0% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| COMPARE_OP | 4,100,980 | 33.7% |
| CALL | 2,382,140 | 19.6% |
| BINARY_OP | 2,057,000 | 16.9% |
| FOR_ITER | 1,500,140 | 12.3% |
| TO_BOOL | 1,000,040 | 8.2% |
| LOAD_ATTR | 630,920 | 5.2% |
| BINARY_SUBSCR | 500,820 | 4.1% |
| LOAD_GLOBAL | 3,360 | 0.0% |
| STORE_ATTR | 2,900 | 0.0% |
| UNPACK_SEQUENCE | 560 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| TO_BOOL_INT | 30,080 | 49.6% |
| TO_BOOL_BOOL | 29,680 | 49.0% |
| LOAD_GLOBAL_BUILTIN | 440 | 0.7% |
| CALL_BOUND_METHOD_EXACT_ARGS | 140 | 0.2% |
| LOAD_ATTR_MODULE | 140 | 0.2% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 60 | 0.1% |
| TO_BOOL_NONE | 40 | 0.1% |
| CALL_METHOD_DESCRIPTOR_O | 20 | 0.0% |
| CACHE | 0 | 0.0% |
| BEFORE_WITH | 0 | 0.0% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 749,760 | 6.9% |
| Calls to Python functions inlined | 10,155,820 | 93.1% |
| Calls via PyEval_EvalFrame (total) | 749,760 | 6.9% |
| Calls via PyEval_EvalFrame (vector) | 749,660 | 6.9% |
| Calls via PyEval_EvalFrame (generator) | 100 | 0.0% |
| Calls via PyEval_EvalFrame (legacy) | 20 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 749,580 | 6.9% |
| Calls via PyEval_EvalFrame (build class) | 60 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 124,840 | 1.1% |
| Calls via PyEval_EvalFrame (function ex) | 100 | 0.0% |
| Calls via PyEval_EvalFrame (api) | 460 | 0.0% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frame objects created | 498,420 | 4.6% |
| Frames pushed | 9,029,240 | 82.8% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 8,882,560 | 30.3% |
| Frees to freelist | 8,882,300 |  |
| Allocations | 20,444,360 | 69.7% |
| Allocations to 512 bytes | 20,061,680 | 68.4% |
| Allocations to 4 kbytes | 132,120 | 0.5% |
| Allocations over 4 kbytes | 250,560 | 0.9% |
| Frees | 20,778,735 |  |
| New values | 124,460 |  |
| Interpreter increfs | 119,901,440 | 84.9% |
| Interpreter decrefs | 134,639,560 | 78.7% |
| Increfs | 21,294,283 | 15.1% |
| Decrefs | 36,538,614 | 21.3% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 0 | 0.0% |
| Method cache hits | 1,509,281 |  |
| Method cache misses | 131,639 |  |
| Method cache collisions | 135,933 |  |
| Method cache dunder hits | 1,493,823 |  |
| Method cache dunder misses | 8,237 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 0 | 0 | 0 |
| 1 | 0 | 0 | 0 |
| 2 | 0 | 0 | 0 |


</details>

## Optimization (Tier 2) stats

<details>
<summary> statistics about the Tier 2 optimizer </summary>

| | Count | Ratio | 
|---|---:|---:|
| Optimization attempts | 2,460 |  |
| Traces created | 160 | 6.5% |
| Trace stack overflow | 0 | 0.0% |
| Trace stack underflow | 0 | 0.0% |
| Trace too long | 0 | 0.0% |
| Trace too short | 2,300 | 93.5% |
| Inner loop found | 0 | 0.0% |
| Recursive call | 0 | 0.0% |
| Traces executed | 679,040 |  |
| Uops executed | 7,852,360 | 11.56 |

### Trace length histogram

<details>
<summary> trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 0 | 0.0% |
| <= 16 | 20 | 12.5% |
| <= 32 | 40 | 25.0% |
| <= 64 | 60 | 37.5% |
| <= 128 | 40 | 25.0% |


</details>

### Optimized trace length histogram

<details>
<summary> optimized trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 20 | 12.5% |
| <= 16 | 20 | 12.5% |
| <= 32 | 60 | 37.5% |
| <= 64 | 60 | 37.5% |


</details>

### Trace run length histogram

<details>
<summary> trace run length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 546,400 | 80.5% |
| <= 16 | 280 | 0.0% |
| <= 32 | 127,460 | 18.8% |
| <= 64 | 4,900 | 0.7% |


</details>

### Uop execution stats

<details>
<summary> uop execution stats </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| _SET_IP | 1,929,460 | 24.6% | 24.6% |  |
| LOAD_FAST | 1,389,740 | 17.7% | 42.3% |  |
| LOAD_CONST | 822,600 | 10.5% | 52.7% |  |
| _EXIT_TRACE | 679,040 | 8.6% | 61.4% |  |
| _GUARD_BOTH_INT | 447,980 | 5.7% | 67.1% |  |
| _BINARY_OP_ADD_INT | 438,420 | 5.6% | 72.7% |  |
| _GUARD_TYPE_VERSION | 139,920 | 1.8% | 74.5% |  |
| STORE_FAST | 137,500 | 1.8% | 76.2% |  |
| _POP_JUMP_IF_TRUE | 130,460 | 1.7% | 77.9% |  |
| _GUARD_GLOBALS_VERSION | 130,160 | 1.7% | 79.5% |  |
| _LOAD_ATTR_METHOD_NO_DICT | 129,820 | 1.7% | 81.2% |  |
| CALL_BUILTIN_FAST | 129,660 | 1.7% | 82.8% |  |
| BINARY_SLICE | 129,600 | 1.7% | 84.5% |  |
| PUSH_NULL | 129,580 | 1.7% | 86.1% |  |
| _POP_JUMP_IF_FALSE | 125,080 | 1.6% | 87.7% |  |
| _IS_NONE | 125,020 | 1.6% | 89.3% |  |
| _GUARD_BUILTINS_VERSION | 124,980 | 1.6% | 90.9% |  |
| _LOAD_GLOBAL_BUILTINS | 124,980 | 1.6% | 92.5% |  |
| _ITER_CHECK_LIST | 124,840 | 1.6% | 94.1% |  |
| _IS_ITER_EXHAUSTED_LIST | 124,840 | 1.6% | 95.7% |  |
| CALL_BUILTIN_O | 124,820 | 1.6% | 97.3% |  |
| POP_TOP | 122,600 | 1.6% | 98.8% |  |
| _BINARY_OP_MULTIPLY_INT | 9,560 | 0.1% | 99.0% |  |
| _CHECK_MANAGED_OBJECT_HAS_VALUES | 7,620 | 0.1% | 99.1% |  |
| _LOAD_ATTR_INSTANCE_VALUE | 7,620 | 0.1% | 99.2% |  |
| _LOAD_GLOBAL_MODULE | 5,180 | 0.1% | 99.2% |  |
| _ITER_CHECK_RANGE | 5,140 | 0.1% | 99.3% |  |
| _IS_ITER_EXHAUSTED_RANGE | 5,140 | 0.1% | 99.4% |  |
| _ITER_NEXT_RANGE | 4,980 | 0.1% | 99.4% |  |
| BINARY_SUBSCR_TUPLE_INT | 4,780 | 0.1% | 99.5% |  |
| _CHECK_ATTR_MODULE | 4,780 | 0.1% | 99.5% |  |
| _LOAD_ATTR_MODULE | 4,780 | 0.1% | 99.6% |  |
| _ITER_NEXT_LIST | 2,600 | 0.0% | 99.6% |  |
| LOAD_DEREF | 2,480 | 0.0% | 99.7% |  |
| RESUME_CHECK | 2,480 | 0.0% | 99.7% |  |
| _GUARD_DORV_VALUES_INST_ATTR_FROM_DICT | 2,480 | 0.0% | 99.7% |  |
| _GUARD_KEYS_VERSION | 2,480 | 0.0% | 99.8% |  |
| _LOAD_ATTR_METHOD_WITH_VALUES | 2,480 | 0.0% | 99.8% |  |
| _CHECK_PEP_523 | 2,480 | 0.0% | 99.8% |  |
| _CHECK_FUNCTION_EXACT_ARGS | 2,480 | 0.0% | 99.9% |  |
| _CHECK_STACK_SPACE | 2,480 | 0.0% | 99.9% |  |
| _INIT_CALL_PY_EXACT_ARGS | 2,480 | 0.0% | 99.9% |  |
| _PUSH_FRAME | 2,480 | 0.0% | 99.9% |  |
| _SAVE_RETURN_OFFSET | 2,480 | 0.0% | 100.0% |  |
| _ITER_CHECK_TUPLE | 280 | 0.0% | 100.0% |  |
| _IS_ITER_EXHAUSTED_TUPLE | 280 | 0.0% | 100.0% |  |
| LIST_APPEND | 160 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 160 | 0.0% | 100.0% |  |
| TO_BOOL_STR | 160 | 0.0% | 100.0% |  |
| _ITER_NEXT_TUPLE | 160 | 0.0% | 100.0% |  |
| _JUMP_TO_TOP | 160 | 0.0% | 100.0% |  |
| CALL_LEN | 80 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_O | 80 | 0.0% | 100.0% |  |
| COMPARE_OP_INT | 80 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 60 | 0.0% | 100.0% |  |
| _GUARD_BOTH_UNICODE | 60 | 0.0% | 100.0% |  |
| _BINARY_OP_ADD_UNICODE | 60 | 0.0% | 100.0% |  |
| TO_BOOL_LIST | 20 | 0.0% | 100.0% |  |


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>

|Opcode | Count | 
|---|---:|
| FOR_ITER_GEN | 1,200 |
| FOR_ITER | 1,100 |
| BINARY_OP | 80 |
| CALL_LIST_APPEND | 40 |
| TO_BOOL | 20 |
| BINARY_SUBSCR_GETITEM | 20 |


</details>


</details>

## Meta stats

<details>
<summary> Meta statistics </summary>

| | Count | 
|---|---:|
| Number of data files | 20 |


</details>

---
Stats gathered on: 2023-11-03
