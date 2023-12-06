
# Pystats results

- benchmark: pyflate
- fork: gvanrossum
- ref: uops-forever
- commit hash: fa8a0d5
- commit date: 2023-09-26T21:50:08-07:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 661,610,380 | 23.3% | 23.3% |  |
| LOAD_CONST | 200,371,760 | 7.0% | 30.3% |  |
| LOAD_ATTR_INSTANCE_VALUE | 176,370,380 | 6.2% | 36.5% |  |
| POP_JUMP_IF_FALSE | 176,287,320 | 6.2% | 42.7% |  |
| COMPARE_OP_INT | 122,851,360 | 4.3% | 47.0% |  |
| BINARY_OP | 111,935,480 | 3.9% | 51.0% |  |
| TO_BOOL_BOOL | 106,050,240 | 3.7% | 54.7% |  |
| SWAP | 93,940,100 | 3.3% | 58.0% |  |
| ENTER_EXECUTOR | 91,897,440 | 3.2% | 61.2% |  |
| LOAD_FAST_LOAD_FAST | 86,335,420 | 3.0% | 64.3% |  |
| COPY | 84,834,340 | 3.0% | 67.3% |  |
| STORE_FAST | 83,077,540 | 2.9% | 70.2% |  |
| BINARY_OP_SUBTRACT_INT | 73,829,940 | 2.6% | 72.8% |  |
| BINARY_OP_ADD_INT | 69,553,860 | 2.4% | 75.2% |  |
| RETURN_VALUE | 61,843,820 | 2.2% | 77.4% |  |
| POP_JUMP_IF_TRUE | 57,138,000 | 2.0% | 79.4% |  |
| RESUME_CHECK | 56,160,880 | 2.0% | 81.4% | 0.0% |
| CALL_PY_EXACT_ARGS | 56,054,440 | 2.0% | 83.4% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 50,474,800 | 1.8% | 85.1% |  |
| BINARY_SUBSCR_LIST_INT | 48,346,440 | 1.7% | 86.8% |  |
| CALL_LIST_APPEND | 46,008,660 | 1.6% | 88.4% |  |
| STORE_SUBSCR_LIST_INT | 40,342,080 | 1.4% | 89.9% |  |
| STORE_ATTR_INSTANCE_VALUE | 35,033,780 | 1.2% | 91.1% |  |
| POP_TOP | 31,958,280 | 1.1% | 92.2% |  |
| LOAD_GLOBAL_BUILTIN | 26,929,140 | 0.9% | 93.2% |  |
| CALL_LEN | 22,351,140 | 0.8% | 94.0% |  |
| STORE_FAST_STORE_FAST | 20,240,460 | 0.7% | 94.7% |  |
| FOR_ITER | 20,191,480 | 0.7% | 95.4% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 20,187,840 | 0.7% | 96.1% |  |
| JUMP_BACKWARD | 20,187,000 | 0.7% | 96.8% |  |
| BINARY_SLICE | 18,264,300 | 0.6% | 97.4% |  |
| RETURN_CONST | 13,728,060 | 0.5% | 97.9% |  |
| UNARY_INVERT | 9,402,480 | 0.3% | 98.2% |  |
| LOAD_ATTR_METHOD_NO_DICT | 8,696,340 | 0.3% | 98.6% |  |
| LOAD_GLOBAL_MODULE | 5,583,760 | 0.2% | 98.8% |  |
| STORE_SLICE | 5,568,180 | 0.2% | 98.9% |  |
| NOP | 5,391,000 | 0.2% | 99.1% |  |
| JUMP_FORWARD | 5,022,600 | 0.2% | 99.3% |  |
| CALL_BUILTIN_O | 4,564,320 | 0.2% | 99.5% |  |
| LOAD_ATTR | 4,053,120 | 0.1% | 99.6% |  |
| TO_BOOL | 4,051,760 | 0.1% | 99.8% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 4,050,800 | 0.1% | 99.9% |  |
| BINARY_SUBSCR | 1,604,260 | 0.1% | 100.0% |  |
| TO_BOOL_INT | 471,920 | 0.0% | 100.0% |  |
| GET_ITER | 184,860 | 0.0% | 100.0% |  |
| FOR_ITER_LIST | 179,300 | 0.0% | 100.0% |  |
| BUILD_LIST | 61,380 | 0.0% | 100.0% |  |
| EXIT_INIT_CHECK | 53,400 | 0.0% | 100.0% |  |
| CALL_ALLOC_AND_ENTER_INIT | 53,400 | 0.0% | 100.0% |  |
| BUILD_TUPLE | 53,280 | 0.0% | 100.0% |  |
| INTERPRETER_EXIT | 52,920 | 0.0% | 100.0% |  |
| BINARY_OP_MULTIPLY_INT | 33,720 | 0.0% | 100.0% |  |
| CALL | 17,100 | 0.0% | 100.0% |  |
| CALL_BUILTIN_CLASS | 12,900 | 0.0% | 100.0% |  |
| CALL_BUILTIN_FAST | 8,760 | 0.0% | 100.0% |  |
| LIST_APPEND | 8,700 | 0.0% | 100.0% |  |
| FOR_ITER_RANGE | 5,900 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 720 | 0.0% | 100.0% |  |
| COMPARE_OP | 420 | 0.0% | 100.0% |  |
| PUSH_NULL | 360 | 0.0% | 100.0% |  |
| CALL_KW | 360 | 0.0% | 100.0% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 240 | 0.0% | 100.0% |  |
| LOAD_ATTR_MODULE | 220 | 0.0% | 100.0% |  |
| LOAD_DEREF | 180 | 0.0% | 100.0% |  |
| STORE_ATTR | 160 | 0.0% | 100.0% |  |
| LOAD_FAST_AND_CLEAR | 120 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_O | 120 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 120 | 0.0% | 100.0% |  |
| CALL_ISINSTANCE | 120 | 0.0% | 100.0% |  |
| CALL_FUNCTION_EX | 120 | 0.0% | 100.0% |  |
| LOAD_FAST_CHECK | 60 | 0.0% | 100.0% |  |
| LIST_EXTEND | 60 | 0.0% | 100.0% |  |
| COPY_FREE_VARS | 60 | 0.0% | 100.0% |  |
| COMPARE_OP_STR | 60 | 0.0% | 100.0% |  |
| CALL_INTRINSIC_1 | 60 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_FLOAT | 60 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| POP_JUMP_IF_FALSE LOAD_FAST | 136,639,200 | 4.8% | 4.8% |
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 129,682,180 | 4.6% | 9.4% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 108,674,980 | 3.8% | 13.2% |
| LOAD_FAST TO_BOOL_BOOL | 106,050,120 | 3.7% | 16.9% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 106,034,880 | 3.7% | 20.6% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 69,780,280 | 2.5% | 23.1% |
| LOAD_FAST LOAD_CONST | 69,100,500 | 2.4% | 25.5% |
| STORE_FAST LOAD_FAST | 62,101,840 | 2.2% | 27.7% |
| LOAD_FAST COMPARE_OP_INT | 61,122,200 | 2.1% | 29.9% |
| LOAD_CONST BINARY_OP_ADD_INT | 57,944,740 | 2.0% | 31.9% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 56,054,440 | 2.0% | 33.9% |
| COMPARE_OP_INT POP_JUMP_IF_TRUE | 53,071,080 | 1.9% | 35.7% |
| ENTER_EXECUTOR LOAD_FAST | 51,469,380 | 1.8% | 37.5% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 50,447,900 | 1.8% | 39.3% |
| LOAD_CONST BINARY_OP_SUBTRACT_INT | 45,131,420 | 1.6% | 40.9% |
| POP_JUMP_IF_TRUE ENTER_EXECUTOR | 44,173,680 | 1.6% | 42.5% |
| LOAD_CONST LOAD_FAST | 43,493,120 | 1.5% | 44.0% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 42,214,540 | 1.5% | 45.5% |
| ENTER_EXECUTOR CALL_LIST_APPEND | 37,245,060 | 1.3% | 46.8% |
| SWAP STORE_ATTR_INSTANCE_VALUE | 34,758,020 | 1.2% | 48.0% |
| LOAD_FAST BINARY_OP | 34,570,240 | 1.2% | 49.2% |
| COPY LOAD_ATTR_INSTANCE_VALUE | 34,548,520 | 1.2% | 50.4% |
| LOAD_FAST COPY | 34,452,400 | 1.2% | 51.7% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 32,962,500 | 1.2% | 52.8% |
| BINARY_OP_ADD_INT SWAP | 32,327,880 | 1.1% | 53.9% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST | 30,705,560 | 1.1% | 55.0% |
| RESUME_CHECK LOAD_CONST | 29,100,920 | 1.0% | 56.1% |
| BINARY_OP_SUBTRACT_INT RETURN_VALUE | 28,917,620 | 1.0% | 57.1% |
| BINARY_OP LOAD_CONST | 28,917,620 | 1.0% | 58.1% |
| LOAD_FAST BINARY_OP_SUBTRACT_INT | 28,664,740 | 1.0% | 59.1% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 26,921,280 | 0.9% | 60.0% |
| BINARY_OP LOAD_FAST | 25,140,860 | 0.9% | 60.9% |
| RETURN_VALUE STORE_FAST | 23,366,580 | 0.8% | 61.7% |
| POP_TOP LOAD_FAST | 22,570,560 | 0.8% | 62.5% |
| LOAD_FAST CALL_LEN | 22,351,060 | 0.8% | 63.3% |
| BINARY_OP_ADD_INT STORE_FAST | 21,901,440 | 0.8% | 64.1% |
| CALL_LIST_APPEND ENTER_EXECUTOR | 20,417,420 | 0.7% | 64.8% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST_STORE_FAST | 20,187,480 | 0.7% | 65.5% |
| JUMP_BACKWARD FOR_ITER | 20,186,400 | 0.7% | 66.2% |
| FOR_ITER UNPACK_SEQUENCE_TWO_TUPLE | 20,186,400 | 0.7% | 66.9% |
| LOAD_FAST_LOAD_FAST BINARY_SUBSCR_LIST_INT | 20,171,100 | 0.7% | 67.7% |
| SWAP SWAP | 20,171,040 | 0.7% | 68.4% |
| SWAP STORE_SUBSCR_LIST_INT | 20,171,040 | 0.7% | 69.1% |
| STORE_SUBSCR_LIST_INT LOAD_FAST_LOAD_FAST | 20,171,040 | 0.7% | 69.8% |
| STORE_SUBSCR_LIST_INT JUMP_BACKWARD | 20,171,040 | 0.7% | 70.5% |
| STORE_FAST_STORE_FAST LOAD_FAST_LOAD_FAST | 20,171,040 | 0.7% | 71.2% |
| LOAD_FAST_LOAD_FAST LOAD_FAST_LOAD_FAST | 20,171,040 | 0.7% | 71.9% |
| LOAD_FAST_LOAD_FAST COPY | 20,171,040 | 0.7% | 72.6% |
| COPY COPY | 20,171,040 | 0.7% | 73.3% |
| COPY BINARY_SUBSCR_LIST_INT | 20,171,040 | 0.7% | 74.0% |
| BINARY_SUBSCR_LIST_INT STORE_SUBSCR_LIST_INT | 20,171,040 | 0.7% | 74.7% |
| BINARY_SUBSCR_LIST_INT LOAD_CONST | 20,171,040 | 0.7% | 75.5% |
| BINARY_OP_SUBTRACT_INT BINARY_OP | 19,524,380 | 0.7% | 76.1% |
| RETURN_VALUE BINARY_OP | 19,515,140 | 0.7% | 76.8% |
| LOAD_FAST LOAD_GLOBAL_BUILTIN | 18,305,400 | 0.6% | 77.5% |
| CALL_LEN COMPARE_OP_INT | 18,298,960 | 0.6% | 78.1% |
| LOAD_FAST LOAD_FAST | 18,287,040 | 0.6% | 78.8% |
| POP_JUMP_IF_FALSE ENTER_EXECUTOR | 18,246,560 | 0.6% | 79.4% |
| CALL_LIST_APPEND LOAD_FAST | 18,120,960 | 0.6% | 80.0% |
| LOAD_CONST COMPARE_OP_INT | 18,032,140 | 0.6% | 80.7% |
| RESUME_CHECK LOAD_FAST_LOAD_FAST | 14,853,320 | 0.5% | 81.2% |
| RETURN_CONST POP_TOP | 13,674,660 | 0.5% | 81.7% |
| LOAD_FAST RETURN_VALUE | 13,507,260 | 0.5% | 82.2% |
| BINARY_OP SWAP | 13,454,040 | 0.5% | 82.6% |
| POP_JUMP_IF_TRUE LOAD_FAST | 12,948,540 | 0.5% | 83.1% |
| BINARY_OP STORE_FAST | 12,844,940 | 0.5% | 83.5% |
| RESUME_CHECK LOAD_FAST | 12,205,440 | 0.4% | 84.0% |
| BINARY_SLICE BINARY_OP | 11,136,360 | 0.4% | 84.4% |
| POP_JUMP_IF_FALSE LOAD_CONST | 10,976,580 | 0.4% | 84.7% |
| LOAD_ATTR_INSTANCE_VALUE STORE_FAST | 10,420,740 | 0.4% | 85.1% |
| BINARY_OP RETURN_VALUE | 10,416,180 | 0.4% | 85.5% |
| SWAP COPY | 9,943,620 | 0.3% | 85.8% |
| COPY COMPARE_OP_INT | 9,943,580 | 0.3% | 86.2% |
| RETURN_VALUE LOAD_FAST | 9,455,400 | 0.3% | 86.5% |
| LOAD_FAST_LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 9,414,800 | 0.3% | 86.8% |
| LOAD_ATTR_INSTANCE_VALUE COMPARE_OP_INT | 9,410,900 | 0.3% | 87.2% |
| UNARY_INVERT BINARY_OP | 9,402,480 | 0.3% | 87.5% |
| LOAD_ATTR_INSTANCE_VALUE BINARY_OP | 9,402,480 | 0.3% | 87.8% |
| BINARY_OP UNARY_INVERT | 9,402,480 | 0.3% | 88.2% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 9,261,420 | 0.3% | 88.5% |
| BINARY_OP_SUBTRACT_INT SWAP | 9,144,980 | 0.3% | 88.8% |
| STORE_FAST LOAD_CONST | 9,085,200 | 0.3% | 89.1% |
| LOAD_ATTR_INSTANCE_VALUE CALL_PY_EXACT_ARGS | 9,074,220 | 0.3% | 89.4% |
| LOAD_FAST SWAP | 8,896,740 | 0.3% | 89.8% |
| RETURN_VALUE POP_TOP | 8,896,440 | 0.3% | 90.1% |
| SWAP POP_TOP | 8,896,260 | 0.3% | 90.4% |
| POP_TOP RETURN_VALUE | 8,896,260 | 0.3% | 90.7% |
| LOAD_ATTR_INSTANCE_VALUE SWAP | 8,896,260 | 0.3% | 91.0% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 8,696,160 | 0.3% | 91.3% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 8,695,440 | 0.3% | 91.6% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_CONST | 8,105,340 | 0.3% | 91.9% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_GLOBAL_BUILTIN | 8,103,120 | 0.3% | 92.2% |
| LOAD_CONST BINARY_OP | 7,670,780 | 0.3% | 92.5% |
| BINARY_OP_ADD_INT BINARY_SLICE | 7,127,580 | 0.3% | 92.7% |
| LOAD_FAST_LOAD_FAST LOAD_CONST | 6,615,060 | 0.2% | 92.9% |
| LOAD_CONST LOAD_CONST | 5,573,160 | 0.2% | 93.1% |
| LOAD_CONST BINARY_SLICE | 5,568,540 | 0.2% | 93.3% |
| BINARY_SUBSCR_LIST_INT STORE_FAST | 5,568,240 | 0.2% | 93.5% |
| STORE_SLICE RETURN_CONST | 5,568,180 | 0.2% | 93.7% |
| LOAD_FAST BINARY_SLICE | 5,568,180 | 0.2% | 93.9% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### BINARY_SLICE

<details>
<summary> Successors and predecessors for BINARY_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 7,127,580 | 39.0% |
| LOAD_CONST | 5,568,540 | 30.5% |
| LOAD_FAST | 5,568,180 | 30.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 11,136,360 | 61.0% |
| LOAD_FAST | 5,568,180 | 30.5% |
| CALL_LIST_APPEND | 534,360 | 2.9% |
| LOAD_GLOBAL_BUILTIN | 512,520 | 2.8% |
| CALL_BUILTIN_O | 512,520 | 2.8% |


</details>

### STORE_SLICE

<details>
<summary> Successors and predecessors for STORE_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 5,568,180 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 5,568,180 | 100.0% |


</details>

### CACHE

<details>
<summary> Successors and predecessors for CACHE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 52,920 | 100.0% |


</details>

### BINARY_SUBSCR

<details>
<summary> Successors and predecessors for BINARY_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 1,603,740 | 100.0% |
| BINARY_SUBSCR | 400 | 0.0% |
| LOAD_FAST_LOAD_FAST | 60 | 0.0% |
| LOAD_FAST | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 1,046,880 | 65.3% |
| COMPARE_OP_INT | 556,860 | 34.7% |
| BINARY_SUBSCR | 400 | 0.0% |
| LOAD_FAST | 60 | 0.0% |
| CALL_LIST_APPEND | 60 | 0.0% |


</details>

### EXIT_INIT_CHECK

<details>
<summary> Successors and predecessors for EXIT_INIT_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 53,400 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 53,400 | 100.0% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 178,680 | 96.7% |
| CALL_BUILTIN_CLASS | 5,700 | 3.1% |
| BINARY_SLICE | 360 | 0.2% |
| LOAD_FAST | 120 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 179,100 | 96.9% |
| FOR_ITER_RANGE | 5,640 | 3.1% |
| LOAD_FAST_AND_CLEAR | 60 | 0.0% |
| FOR_ITER | 60 | 0.0% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 52,920 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_LIST_APPEND | 5,390,220 | 100.0% |
| POP_JUMP_IF_FALSE | 600 | 0.0% |
| STORE_FAST | 120 | 0.0% |
| POP_TOP | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 5,390,220 | 100.0% |
| LOAD_FAST | 720 | 0.0% |
| LOAD_DEREF | 60 | 0.0% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 13,674,660 | 42.8% |
| RETURN_VALUE | 8,896,440 | 27.8% |
| SWAP | 8,896,260 | 27.8% |
| POP_JUMP_IF_FALSE | 490,020 | 1.5% |
| POP_JUMP_IF_TRUE | 360 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 22,570,560 | 70.6% |
| RETURN_VALUE | 8,896,260 | 27.8% |
| JUMP_FORWARD | 490,500 | 1.5% |
| RETURN_CONST | 420 | 0.0% |
| LOAD_FAST_LOAD_FAST | 360 | 0.0% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 220 | 61.1% |
| LOAD_DEREF | 120 | 33.3% |
| LOAD_ATTR | 20 | 5.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 180 | 50.0% |
| LOAD_FAST | 120 | 33.3% |
| LOAD_FAST_CHECK | 60 | 16.7% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_SUBTRACT_INT | 28,917,620 | 46.8% |
| LOAD_FAST | 13,507,260 | 21.8% |
| BINARY_OP | 10,416,180 | 16.8% |
| POP_TOP | 8,896,260 | 14.4% |
| EXIT_INIT_CHECK | 53,400 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 23,366,580 | 37.8% |
| BINARY_OP | 19,515,140 | 31.6% |
| LOAD_FAST | 9,455,400 | 15.3% |
| POP_TOP | 8,896,440 | 14.4% |
| TO_BOOL_INT | 470,460 | 0.8% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,050,760 | 100.0% |
| TO_BOOL | 980 | 0.0% |
| CALL_LEN | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 4,050,740 | 100.0% |
| TO_BOOL | 980 | 0.0% |
| TO_BOOL_INT | 40 | 0.0% |


</details>

### UNARY_INVERT

<details>
<summary> Successors and predecessors for UNARY_INVERT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 9,402,480 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 9,402,480 | 100.0% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 34,570,240 | 30.9% |
| BINARY_OP_SUBTRACT_INT | 19,524,380 | 17.4% |
| RETURN_VALUE | 19,515,140 | 17.4% |
| BINARY_SLICE | 11,136,360 | 9.9% |
| UNARY_INVERT | 9,402,480 | 8.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 28,917,620 | 25.8% |
| LOAD_FAST | 25,140,860 | 22.5% |
| SWAP | 13,454,040 | 12.0% |
| STORE_FAST | 12,844,940 | 11.5% |
| RETURN_VALUE | 10,416,180 | 9.3% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 53,280 | 86.8% |
| CALL_BUILTIN_CLASS | 6,300 | 10.3% |
| STORE_FAST | 540 | 0.9% |
| RESUME_CHECK | 480 | 0.8% |
| BUILD_TUPLE | 360 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 59,940 | 97.7% |
| STORE_FAST | 1,200 | 2.0% |
| SWAP | 60 | 0.1% |
| LOAD_DEREF | 60 | 0.1% |
| LOAD_CONST | 60 | 0.1% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 52,920 | 99.3% |
| LOAD_CONST | 360 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 52,920 | 99.3% |
| BUILD_LIST | 360 | 0.7% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 15,300 | 89.5% |
| LOAD_FAST | 840 | 4.9% |
| LOAD_CONST | 300 | 1.8% |
| PUSH_NULL | 180 | 1.1% |
| CALL | 160 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_LIST_APPEND | 15,360 | 89.8% |
| CALL_BUILTIN_CLASS | 540 | 3.2% |
| CALL_PY_EXACT_ARGS | 360 | 2.1% |
| CALL | 160 | 0.9% |
| STORE_FAST | 120 | 0.7% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60 | 50.0% |
| CALL_INTRINSIC_1 | 60 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 60 | 50.0% |
| COPY_FREE_VARS | 60 | 50.0% |


</details>

### CALL_INTRINSIC_1

<details>
<summary> Successors and predecessors for CALL_INTRINSIC_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LIST_EXTEND | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 60 | 100.0% |


</details>

### CALL_KW

<details>
<summary> Successors and predecessors for CALL_KW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 360 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 360 | 100.0% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 280 | 66.7% |
| COPY | 40 | 9.5% |
| COMPARE_OP | 40 | 9.5% |
| CALL_BUILTIN_O | 40 | 9.5% |
| CALL_LEN | 20 | 4.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 180 | 42.9% |
| COMPARE_OP_INT | 180 | 42.9% |
| COMPARE_OP | 40 | 9.5% |
| COMPARE_OP_STR | 20 | 4.8% |


</details>

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 34,452,400 | 40.6% |
| LOAD_FAST_LOAD_FAST | 20,171,040 | 23.8% |
| COPY | 20,171,040 | 23.8% |
| SWAP | 9,943,620 | 11.7% |
| ENTER_EXECUTOR | 96,120 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 34,548,520 | 40.7% |
| COPY | 20,171,040 | 23.8% |
| BINARY_SUBSCR_LIST_INT | 20,171,040 | 23.8% |
| COMPARE_OP_INT | 9,943,580 | 11.7% |
| STORE_FAST_STORE_FAST | 60 | 0.0% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 60 | 100.0% |


</details>

### ENTER_EXECUTOR

<details>
<summary> Successors and predecessors for ENTER_EXECUTOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 44,173,680 | 48.1% |
| CALL_LIST_APPEND | 20,417,420 | 22.2% |
| POP_JUMP_IF_FALSE | 18,246,560 | 19.9% |
| NOP | 5,390,220 | 5.9% |
| STORE_FAST | 3,611,960 | 3.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 51,469,380 | 56.0% |
| CALL_LIST_APPEND | 37,245,060 | 40.5% |
| LOAD_ATTR_INSTANCE_VALUE | 2,724,780 | 3.0% |
| LOAD_CONST | 177,960 | 0.2% |
| COPY | 96,120 | 0.1% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 20,186,400 | 100.0% |
| FOR_ITER | 4,960 | 0.0% |
| SWAP | 60 | 0.0% |
| GET_ITER | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 20,186,400 | 100.0% |
| FOR_ITER | 4,960 | 0.0% |
| STORE_FAST | 60 | 0.0% |
| LOAD_FAST | 60 | 0.0% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_SUBSCR_LIST_INT | 20,171,040 | 99.9% |
| LIST_APPEND | 8,700 | 0.0% |
| POP_JUMP_IF_TRUE | 6,660 | 0.0% |
| STORE_FAST | 280 | 0.0% |
| CALL_LIST_APPEND | 220 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 20,186,400 | 100.0% |
| FOR_ITER_RANGE | 260 | 0.0% |
| FOR_ITER_LIST | 200 | 0.0% |
| LOAD_FAST | 60 | 0.0% |
| ENTER_EXECUTOR | 60 | 0.0% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 4,019,100 | 80.0% |
| STORE_FAST | 512,580 | 10.2% |
| POP_TOP | 490,500 | 9.8% |
| ENTER_EXECUTOR | 420 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,022,360 | 100.0% |
| LOAD_CONST | 60 | 0.0% |
| JUMP_BACKWARD | 60 | 0.0% |
| BUILD_LIST | 60 | 0.0% |
| LOAD_GLOBAL_MODULE | 40 | 0.0% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_FAST | 8,700 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 8,700 | 100.0% |


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_DEREF | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 60 | 100.0% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 4,050,740 | 99.9% |
| LOAD_ATTR | 1,060 | 0.0% |
| LOAD_GLOBAL_MODULE | 800 | 0.0% |
| LOAD_FAST | 440 | 0.0% |
| LOAD_CONST | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,050,740 | 99.9% |
| LOAD_ATTR | 1,060 | 0.0% |
| LOAD_CONST | 420 | 0.0% |
| LOAD_FAST_LOAD_FAST | 360 | 0.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 220 | 0.0% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 69,100,500 | 34.5% |
| RESUME_CHECK | 29,100,920 | 14.5% |
| BINARY_OP | 28,917,620 | 14.4% |
| BINARY_SUBSCR_LIST_INT | 20,171,040 | 10.1% |
| POP_JUMP_IF_FALSE | 10,976,580 | 5.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 57,944,740 | 28.9% |
| BINARY_OP_SUBTRACT_INT | 45,131,420 | 22.5% |
| LOAD_FAST | 43,493,120 | 21.7% |
| COMPARE_OP_INT | 18,032,140 | 9.0% |
| BINARY_OP | 7,670,780 | 3.8% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 60 | 33.3% |
| NOP | 60 | 33.3% |
| BUILD_LIST | 60 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 120 | 66.7% |
| LIST_EXTEND | 60 | 33.3% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 136,639,200 | 20.7% |
| LOAD_ATTR_INSTANCE_VALUE | 108,674,980 | 16.4% |
| STORE_FAST | 62,101,840 | 9.4% |
| ENTER_EXECUTOR | 51,469,380 | 7.8% |
| LOAD_CONST | 43,493,120 | 6.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 129,682,180 | 19.6% |
| TO_BOOL_BOOL | 106,050,120 | 16.0% |
| LOAD_CONST | 69,100,500 | 10.4% |
| COMPARE_OP_INT | 61,122,200 | 9.2% |
| LOAD_ATTR_METHOD_WITH_VALUES | 50,447,900 | 7.6% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_AND_CLEAR | 60 | 50.0% |
| GET_ITER | 60 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 60 | 50.0% |
| LOAD_FAST_AND_CLEAR | 60 | 50.0% |


</details>

### LOAD_FAST_CHECK

<details>
<summary> Successors and predecessors for LOAD_FAST_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 40 | 66.7% |
| CALL | 20 | 33.3% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_SUBSCR_LIST_INT | 20,171,040 | 23.4% |
| STORE_FAST_STORE_FAST | 20,171,040 | 23.4% |
| LOAD_FAST_LOAD_FAST | 20,171,040 | 23.4% |
| RESUME_CHECK | 14,853,320 | 17.2% |
| BINARY_OP | 5,568,180 | 6.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_LIST_INT | 20,171,100 | 23.4% |
| LOAD_FAST_LOAD_FAST | 20,171,040 | 23.4% |
| COPY | 20,171,040 | 23.4% |
| LOAD_ATTR_INSTANCE_VALUE | 9,414,800 | 10.9% |
| LOAD_FAST | 9,261,420 | 10.7% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 280 | 38.9% |
| POP_JUMP_IF_FALSE | 80 | 11.1% |
| RESUME_CHECK | 60 | 8.3% |
| LOAD_GLOBAL_BUILTIN | 60 | 8.3% |
| LOAD_FAST | 60 | 8.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 440 | 61.1% |
| LOAD_GLOBAL_MODULE | 260 | 36.1% |
| LOAD_ATTR | 20 | 2.8% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 106,034,880 | 60.1% |
| COMPARE_OP_INT | 69,780,280 | 39.6% |
| TO_BOOL_INT | 471,920 | 0.3% |
| COMPARE_OP | 180 | 0.0% |
| COMPARE_OP_STR | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 136,639,200 | 77.5% |
| ENTER_EXECUTOR | 18,246,560 | 10.4% |
| LOAD_CONST | 10,976,580 | 6.2% |
| RETURN_CONST | 4,051,620 | 2.3% |
| JUMP_FORWARD | 4,019,100 | 2.3% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 53,071,080 | 92.9% |
| TO_BOOL | 4,050,740 | 7.1% |
| TO_BOOL_BOOL | 15,360 | 0.0% |
| ENTER_EXECUTOR | 820 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 44,173,680 | 77.3% |
| LOAD_FAST | 12,948,540 | 22.7% |
| LOAD_GLOBAL_MODULE | 8,740 | 0.0% |
| JUMP_BACKWARD | 6,660 | 0.0% |
| POP_TOP | 360 | 0.0% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_SLICE | 5,568,180 | 40.6% |
| STORE_ATTR_INSTANCE_VALUE | 4,107,120 | 29.9% |
| POP_JUMP_IF_FALSE | 4,051,620 | 29.5% |
| ENTER_EXECUTOR | 720 | 0.0% |
| POP_TOP | 420 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 13,674,660 | 99.6% |
| EXIT_INIT_CHECK | 53,400 | 0.4% |


</details>

### STORE_ATTR

<details>
<summary> Successors and predecessors for STORE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 140 | 87.5% |
| LOAD_FAST_LOAD_FAST | 20 | 12.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 160 | 100.0% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 23,366,580 | 28.1% |
| BINARY_OP_ADD_INT | 21,901,440 | 26.4% |
| BINARY_OP | 12,844,940 | 15.5% |
| LOAD_ATTR_INSTANCE_VALUE | 10,420,740 | 12.5% |
| BINARY_SUBSCR_LIST_INT | 5,568,240 | 6.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 62,101,840 | 74.8% |
| LOAD_CONST | 9,085,200 | 10.9% |
| LOAD_GLOBAL_MODULE | 5,390,940 | 6.5% |
| ENTER_EXECUTOR | 3,611,960 | 4.3% |
| LOAD_FAST_LOAD_FAST | 2,367,840 | 2.9% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 20,187,480 | 99.7% |
| LOAD_FAST_LOAD_FAST | 52,920 | 0.3% |
| COPY | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 20,171,040 | 99.7% |
| LOAD_FAST | 69,360 | 0.3% |
| BUILD_LIST | 60 | 0.0% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 32,327,880 | 34.4% |
| SWAP | 20,171,040 | 21.5% |
| BINARY_OP | 13,454,040 | 14.3% |
| BINARY_OP_SUBTRACT_INT | 9,144,980 | 9.7% |
| LOAD_FAST | 8,896,740 | 9.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 34,758,020 | 37.0% |
| SWAP | 20,171,040 | 21.5% |
| STORE_SUBSCR_LIST_INT | 20,171,040 | 21.5% |
| COPY | 9,943,620 | 10.6% |
| POP_TOP | 8,896,260 | 9.5% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 57,944,740 | 83.3% |
| CALL_LEN | 4,051,560 | 5.8% |
| CALL_BUILTIN_O | 4,051,560 | 5.8% |
| BINARY_OP | 3,506,000 | 5.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 32,327,880 | 46.5% |
| STORE_FAST | 21,901,440 | 31.5% |
| BINARY_SLICE | 7,127,580 | 10.2% |
| LOAD_CONST | 5,568,180 | 8.0% |
| BINARY_SUBSCR | 1,603,740 | 2.3% |


</details>

### BINARY_OP_MULTIPLY_INT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 33,720 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 33,720 | 100.0% |


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
| LOAD_CONST | 45,131,420 | 61.1% |
| LOAD_FAST | 28,664,740 | 38.8% |
| BINARY_OP_SUBTRACT_INT | 33,720 | 0.0% |
| CALL_BUILTIN_O | 40 | 0.0% |
| BINARY_OP | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 28,917,620 | 39.2% |
| BINARY_OP | 19,524,380 | 26.4% |
| SWAP | 9,144,980 | 12.4% |
| COMPARE_OP_INT | 5,390,340 | 7.3% |
| CALL_PY_EXACT_ARGS | 5,390,220 | 7.3% |


</details>

### BINARY_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 20,171,100 | 41.7% |
| COPY | 20,171,040 | 41.7% |
| BINARY_OP_SUBTRACT_INT | 5,390,220 | 11.1% |
| LOAD_CONST | 2,258,160 | 4.7% |
| LOAD_FAST | 177,960 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_SUBSCR_LIST_INT | 20,171,040 | 41.7% |
| LOAD_CONST | 20,171,040 | 41.7% |
| STORE_FAST | 5,568,240 | 11.5% |
| LOAD_FAST | 2,079,840 | 4.3% |
| CALL_LIST_APPEND | 177,960 | 0.4% |


</details>

### CALL_ALLOC_AND_ENTER_INIT

<details>
<summary> Successors and predecessors for CALL_ALLOC_AND_ENTER_INIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 52,680 | 98.7% |
| LOAD_FAST_LOAD_FAST | 360 | 0.7% |
| LOAD_FAST | 320 | 0.6% |
| CALL | 40 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 53,400 | 100.0% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 6,300 | 48.8% |
| LOAD_CONST | 4,660 | 36.1% |
| LOAD_FAST | 960 | 7.4% |
| CALL | 540 | 4.2% |
| LOAD_FAST_LOAD_FAST | 360 | 2.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BUILD_LIST | 6,300 | 48.8% |
| GET_ITER | 5,700 | 44.2% |
| LOAD_FAST | 720 | 5.6% |
| STORE_FAST | 120 | 0.9% |
| CALL_BUILTIN_CLASS | 40 | 0.3% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,760 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LIST_APPEND | 8,700 | 99.3% |
| CALL | 60 | 0.7% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 80 | 33.3% |
| CALL | 80 | 33.3% |
| LOAD_FAST_CHECK | 40 | 16.7% |
| LOAD_CONST | 40 | 16.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 60 | 25.0% |
| LOAD_CONST | 60 | 25.0% |
| CALL | 60 | 25.0% |
| LOAD_ATTR_METHOD_NO_DICT | 40 | 16.7% |
| LOAD_ATTR | 20 | 8.3% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,051,560 | 88.8% |
| BINARY_SLICE | 512,520 | 11.2% |
| LOAD_CONST | 160 | 0.0% |
| CALL | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 4,051,560 | 88.8% |
| LOAD_CONST | 512,520 | 11.2% |
| COMPARE_OP_INT | 80 | 0.0% |
| LOAD_FAST | 60 | 0.0% |
| COMPARE_OP | 40 | 0.0% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 120 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 120 | 100.0% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 22,351,060 | 100.0% |
| CALL | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 18,298,960 | 81.9% |
| BINARY_OP_ADD_INT | 4,051,560 | 18.1% |
| STORE_FAST | 360 | 0.0% |
| LOAD_CONST | 60 | 0.0% |
| BINARY_OP | 60 | 0.0% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 37,245,060 | 81.0% |
| LOAD_FAST | 5,390,580 | 11.7% |
| BINARY_OP | 2,592,360 | 5.6% |
| BINARY_SLICE | 534,360 | 1.2% |
| BINARY_SUBSCR_LIST_INT | 177,960 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 20,417,420 | 44.4% |
| LOAD_FAST | 18,120,960 | 39.4% |
| NOP | 5,390,220 | 11.7% |
| LOAD_CONST | 2,079,840 | 4.5% |
| JUMP_BACKWARD | 220 | 0.0% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,050,740 | 100.0% |
| LOAD_CONST | 40 | 0.0% |
| CALL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 4,050,740 | 100.0% |
| POP_TOP | 60 | 0.0% |


</details>

### CALL_METHOD_DESCRIPTOR_NOARGS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_NOARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 40 | 33.3% |
| LOAD_ATTR | 40 | 33.3% |
| CALL | 40 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 60 | 50.0% |
| LOAD_CONST | 60 | 50.0% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 80 | 66.7% |
| CALL | 40 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 60 | 50.0% |
| LOAD_FAST | 60 | 50.0% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 32,962,500 | 58.8% |
| LOAD_ATTR_INSTANCE_VALUE | 9,074,220 | 16.2% |
| BINARY_OP_SUBTRACT_INT | 5,390,220 | 9.6% |
| LOAD_CONST | 4,386,480 | 7.8% |
| LOAD_ATTR_METHOD_WITH_VALUES | 4,051,540 | 7.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 56,054,440 | 100.0% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 61,122,200 | 49.8% |
| CALL_LEN | 18,298,960 | 14.9% |
| LOAD_CONST | 18,032,140 | 14.7% |
| COPY | 9,943,580 | 8.1% |
| LOAD_ATTR_INSTANCE_VALUE | 9,410,900 | 7.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 69,780,280 | 56.8% |
| POP_JUMP_IF_TRUE | 53,071,080 | 43.2% |


</details>

### COMPARE_OP_STR

<details>
<summary> Successors and predecessors for COMPARE_OP_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 40 | 66.7% |
| COMPARE_OP | 20 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 60 | 100.0% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 179,100 | 99.9% |
| JUMP_BACKWARD | 200 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 178,920 | 99.8% |
| UNPACK_SEQUENCE_TWO_TUPLE | 360 | 0.2% |
| LOAD_FAST | 20 | 0.0% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 5,640 | 95.6% |
| JUMP_BACKWARD | 260 | 4.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 5,820 | 98.6% |
| LOAD_GLOBAL_MODULE | 40 | 0.7% |
| LOAD_GLOBAL | 20 | 0.3% |
| BUILD_LIST | 20 | 0.3% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 129,682,180 | 73.5% |
| COPY | 34,548,520 | 19.6% |
| LOAD_FAST_LOAD_FAST | 9,414,800 | 5.3% |
| ENTER_EXECUTOR | 2,724,780 | 1.5% |
| LOAD_ATTR | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 108,674,980 | 61.6% |
| STORE_FAST | 10,420,740 | 5.9% |
| COMPARE_OP_INT | 9,410,900 | 5.3% |
| BINARY_OP | 9,402,480 | 5.3% |
| CALL_PY_EXACT_ARGS | 9,074,220 | 5.1% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,696,160 | 100.0% |
| LOAD_CONST | 80 | 0.0% |
| LOAD_ATTR | 60 | 0.0% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,695,440 | 100.0% |
| LOAD_GLOBAL_MODULE | 780 | 0.0% |
| LOAD_FAST_LOAD_FAST | 60 | 0.0% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 40 | 0.0% |
| CALL | 20 | 0.0% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 50,447,900 | 99.9% |
| LOAD_FAST_LOAD_FAST | 26,640 | 0.1% |
| LOAD_ATTR | 220 | 0.0% |
| ENTER_EXECUTOR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 42,214,540 | 83.6% |
| LOAD_CONST | 4,208,680 | 8.3% |
| CALL_PY_EXACT_ARGS | 4,051,540 | 8.0% |
| CALL | 40 | 0.0% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 140 | 63.6% |
| LOAD_ATTR | 80 | 36.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 220 | 100.0% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 18,305,400 | 68.0% |
| LOAD_ATTR_INSTANCE_VALUE | 8,103,120 | 30.1% |
| BINARY_SLICE | 512,520 | 1.9% |
| STORE_FAST | 5,780 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 840 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 26,921,280 | 100.0% |
| LOAD_FAST_LOAD_FAST | 6,660 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 840 | 0.0% |
| LOAD_CONST | 300 | 0.0% |
| LOAD_GLOBAL | 60 | 0.0% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 5,390,940 | 96.5% |
| POP_JUMP_IF_FALSE | 178,080 | 3.2% |
| POP_JUMP_IF_TRUE | 8,740 | 0.2% |
| STORE_ATTR_INSTANCE_VALUE | 4,620 | 0.1% |
| LOAD_ATTR_METHOD_NO_DICT | 780 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,399,520 | 96.7% |
| LOAD_FAST_LOAD_FAST | 183,120 | 3.3% |
| LOAD_ATTR | 800 | 0.0% |
| LOAD_ATTR_MODULE | 140 | 0.0% |
| CALL_ISINSTANCE | 120 | 0.0% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 56,054,440 | 99.8% |
| CALL_ALLOC_AND_ENTER_INIT | 53,400 | 0.1% |
| CACHE | 52,920 | 0.1% |
| COPY_FREE_VARS | 60 | 0.0% |
| CALL_FUNCTION_EX | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 29,100,920 | 51.8% |
| LOAD_FAST_LOAD_FAST | 14,853,320 | 26.4% |
| LOAD_FAST | 12,205,440 | 21.7% |
| LOAD_GLOBAL_BUILTIN | 560 | 0.0% |
| BUILD_LIST | 480 | 0.0% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 34,758,020 | 99.2% |
| LOAD_FAST | 164,740 | 0.5% |
| LOAD_FAST_LOAD_FAST | 110,860 | 0.3% |
| STORE_ATTR | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 30,705,560 | 87.6% |
| RETURN_CONST | 4,107,120 | 11.7% |
| LOAD_CONST | 106,020 | 0.3% |
| ENTER_EXECUTOR | 57,540 | 0.2% |
| LOAD_FAST_LOAD_FAST | 52,920 | 0.2% |


</details>

### STORE_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 20,171,040 | 50.0% |
| BINARY_SUBSCR_LIST_INT | 20,171,040 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 20,171,040 | 50.0% |
| JUMP_BACKWARD | 20,171,040 | 50.0% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 106,050,120 | 100.0% |
| CALL_ISINSTANCE | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 106,034,880 | 100.0% |
| POP_JUMP_IF_TRUE | 15,360 | 0.0% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 470,460 | 99.7% |
| BINARY_OP | 980 | 0.2% |
| LOAD_FAST | 400 | 0.1% |
| TO_BOOL | 40 | 0.0% |
| CALL_LEN | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 471,920 | 100.0% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 20,186,400 | 100.0% |
| LOAD_CONST | 720 | 0.0% |
| FOR_ITER_LIST | 360 | 0.0% |
| BINARY_SUBSCR_LIST_INT | 360 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 20,187,480 | 100.0% |
| LOAD_FAST | 360 | 0.0% |


</details>


</details>

## Specialization stats

<details>
<summary> specialization stats by family </summary>

### BINARY_SLICE

<details>
<summary> specialization stats for BINARY_SLICE family </summary>

|Kind | Count | Ratio | 
|---|---|---|


</details>

### STORE_SLICE

<details>
<summary> specialization stats for STORE_SLICE family </summary>

|Kind | Count | Ratio | 
|---|---|---|


</details>

### BINARY_SUBSCR

<details>
<summary> specialization stats for BINARY_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      1603860 | 2.3% |
|          hit |     68517420 | 97.7% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 0 | 0.0% |
| Failure | 400 | 100.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| buffer int | 400 | 100.0% |


</details>

### STORE_SUBSCR

<details>
<summary> specialization stats for STORE_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |     40342080 | 100.0% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      4050740 | 3.7% |
|          hit |    106589100 | 96.3% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 40 | 3.9% |
| Failure | 980 | 96.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| bytes | 980 | 100.0% |


</details>

### BINARY_OP

<details>
<summary> specialization stats for BINARY_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |    111907520 | 33.0% |
|          hit |    226917180 | 67.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 60 | 0.2% |
| Failure | 27,900 | 99.8% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| lshift | 12,220 | 43.8% |
| and int | 7,200 | 25.8% |
| rshift | 4,900 | 17.6% |
| add other | 2,840 | 10.2% |
| multiply different types | 660 | 2.4% |
| or | 80 | 0.3% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |        16020 | 0.0% |
|          hit |    191180580 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 920 | 85.2% |
| Failure | 160 | 14.8% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| class no vectorcall | 60 | 37.5% |
| cfunc noargs | 60 | 37.5% |
| meth descr varargs | 40 | 25.0% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |          180 | 0.0% |
|          hit |    241876620 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 200 | 83.3% |
| Failure | 40 | 16.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| big int | 40 | 100.0% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |     20186520 | 99.1% |
|          hit |       185200 | 0.9% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 0 | 0.0% |
| Failure | 4,960 | 100.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| enumerate | 4,960 | 100.0% |


</details>

### JUMP_BACKWARD

<details>
<summary> specialization stats for JUMP_BACKWARD family </summary>

|Kind | Count | Ratio | 
|---|---|---|


</details>

### LOAD_ATTR

<details>
<summary> specialization stats for LOAD_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      4051600 | 0.9% |
|          hit |    456658720 | 99.1% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 460 | 30.3% |
| Failure | 1,060 | 69.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| not managed dict | 1,020 | 96.2% |
| metaclass attribute | 20 | 1.9% |
| non overriding descriptor | 20 | 1.9% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |           20 | 0.0% |
|          hit |     50863360 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 700 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> specialization stats for POP_JUMP_IF_FALSE family </summary>

|Kind | Count | Ratio | 
|---|---|---|


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> specialization stats for POP_JUMP_IF_TRUE family </summary>

|Kind | Count | Ratio | 
|---|---|---|


</details>

### STORE_ATTR

<details>
<summary> specialization stats for STORE_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |     35343900 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 160 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |     20240400 | 100.0% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 1,450,069,600 | 51.0% |
| Not specialized | 419,299,360 | 14.7% |
| Specialized | 974,206,980 | 34.3% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| RESUME | 368,934,881,474,191,032,260 | 100.0% |
| BINARY_OP | 111,907,520 | 0.0% |
| FOR_ITER | 20,186,520 | 0.0% |
| LOAD_ATTR | 4,051,600 | 0.0% |
| TO_BOOL | 4,050,740 | 0.0% |
| BINARY_SUBSCR | 1,603,860 | 0.0% |
| CALL | 16,020 | 0.0% |
| COMPARE_OP | 180 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 0 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| RESUME_CHECK | 60 | 50.0% |
| RESUME | 60 | 50.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 0 | 0.0% |
| UNARY_INVERT | 0 | 0.0% |
| TO_BOOL_INT | 0 | 0.0% |
| TO_BOOL_BOOL | 0 | 0.0% |
| SWAP | 0 | 0.0% |
| STORE_SUBSCR_LIST_INT | 0 | 0.0% |
| STORE_FAST_STORE_FAST | 0 | 0.0% |
| STORE_FAST | 0 | 0.0% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 52,920 | 0.1% |
| Calls to Python functions inlined | 95,931,060 | 99.9% |
| Calls via PyEval_EvalFrame (total) | 52,920 | 0.1% |
| Calls via PyEval_EvalFrame (vector) | 52,920 | 0.1% |
| Calls via PyEval_EvalFrame (generator) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 52,920 | 0.1% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function ex) | 120 | 0.0% |
| Calls via PyEval_EvalFrame (api) | 52,920 | 0.1% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frames pushed | 96,037,380 | 100.1% |
| Frame objects created | 0 | 0.0% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 28,034,640 | 10.4% |
| Frees to freelist | 28,035,060 |  |
| Allocations | 242,225,820 | 89.6% |
| Allocations to 512 bytes | 225,976,040 | 83.6% |
| Allocations to 4 kbytes | 16,248,460 | 6.0% |
| Allocations over 4 kbytes | 1,320 | 0.0% |
| Frees | 242,226,060 |  |
| New values | 0 |  |
| Interpreter increfs | 798,562,380 | 48.8% |
| Interpreter decrefs | 1,065,768,860 | 55.7% |
| Increfs | 836,221,295 | 51.2% |
| Decrefs | 846,912,255 | 44.3% |
| Materialize dict (on request) | 0 |  |
| Materialize dict (new key) | 0 |  |
| Materialize dict (too big) | 0 |  |
| Materialize dict (str subclass) | 0 |  |
| Dematerialize dict | 0 |  |
| Method cache hits | 4,058,487 |  |
| Method cache misses | 33 |  |
| Method cache collisions | 33 |  |
| Method cache dunder hits | 1,720 |  |
| Method cache dunder misses | 0 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 60 | 0 | 1,060,320 |
| 1 | 0 | 0 | 0 |
| 2 | 0 | 0 | 0 |


</details>

## Meta stats

<details>
<summary> Meta statistics </summary>

| | Count | 
|---|---:|
| Number of data files | 20 |


</details>

---
Stats gathered on: 2023-09-27
