
# Pystats results

- benchmark: scimark
- fork: gvanrossum
- ref: uops-forever
- commit hash: fa8a0d5
- commit date: 2023-09-26T21:50:08-07:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 825,405,900 | 18.6% | 18.6% |  |
| LOAD_FAST_LOAD_FAST | 330,635,160 | 7.4% | 26.0% |  |
| POP_JUMP_IF_FALSE | 249,746,460 | 5.6% | 31.7% |  |
| LOAD_ATTR_INSTANCE_VALUE | 243,885,240 | 5.5% | 37.2% |  |
| LOAD_CONST | 227,232,120 | 5.1% | 42.3% |  |
| SWAP | 219,881,040 | 5.0% | 47.2% |  |
| COPY | 207,718,800 | 4.7% | 51.9% |  |
| BINARY_SUBSCR | 175,609,480 | 4.0% | 55.9% |  |
| COMPARE_OP_INT | 170,082,780 | 3.8% | 59.7% |  |
| RESUME_CHECK | 136,703,580 | 3.1% | 62.8% |  |
| RETURN_VALUE | 135,842,700 | 3.1% | 65.8% |  |
| LOAD_GLOBAL_BUILTIN | 133,733,340 | 3.0% | 68.8% |  |
| STORE_SUBSCR | 132,660,980 | 3.0% | 71.8% |  |
| BINARY_OP_ADD_INT | 118,886,160 | 2.7% | 74.5% |  |
| STORE_FAST | 99,940,980 | 2.3% | 76.8% |  |
| BINARY_OP_ADD_FLOAT | 90,549,780 | 2.0% | 78.8% |  |
| BINARY_SUBSCR_GETITEM | 88,538,340 | 2.0% | 80.8% |  |
| BINARY_OP_MULTIPLY_FLOAT | 81,016,980 | 1.8% | 82.6% |  |
| ENTER_EXECUTOR | 79,736,520 | 1.8% | 84.4% |  |
| TO_BOOL_BOOL | 73,060,620 | 1.6% | 86.1% |  |
| JUMP_FORWARD | 70,645,560 | 1.6% | 87.6% |  |
| BINARY_OP_SUBTRACT_FLOAT | 69,083,820 | 1.6% | 89.2% |  |
| CALL_ISINSTANCE | 60,337,740 | 1.4% | 90.6% |  |
| BINARY_SUBSCR_LIST_INT | 60,326,340 | 1.4% | 91.9% |  |
| STORE_FAST_STORE_FAST | 41,780,580 | 0.9% | 92.9% |  |
| CALL_PY_EXACT_ARGS | 41,190,480 | 0.9% | 93.8% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 41,174,940 | 0.9% | 94.7% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 35,180,400 | 0.8% | 95.5% |  |
| BINARY_OP_MULTIPLY_INT | 35,036,880 | 0.8% | 96.3% |  |
| BINARY_OP_SUBTRACT_INT | 30,539,940 | 0.7% | 97.0% |  |
| BUILD_TUPLE | 29,412,240 | 0.7% | 97.6% |  |
| STORE_ATTR_INSTANCE_VALUE | 25,447,740 | 0.6% | 98.2% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 19,097,160 | 0.4% | 98.7% | 0.1% |
| CALL_BUILTIN_CLASS | 13,051,380 | 0.3% | 98.9% |  |
| BINARY_OP | 9,640,780 | 0.2% | 99.2% |  |
| COMPARE_OP | 6,607,820 | 0.1% | 99.3% |  |
| RETURN_CONST | 6,392,640 | 0.1% | 99.5% |  |
| INTERPRETER_EXIT | 6,373,980 | 0.1% | 99.6% |  |
| POP_JUMP_IF_TRUE | 6,303,000 | 0.1% | 99.7% |  |
| COMPARE_OP_FLOAT | 6,297,000 | 0.1% | 99.9% |  |
| BINARY_SUBSCR_TUPLE_INT | 1,200,000 | 0.0% | 99.9% |  |
| POP_TOP | 618,840 | 0.0% | 99.9% |  |
| JUMP_BACKWARD | 606,460 | 0.0% | 99.9% |  |
| FOR_ITER_GEN | 600,060 | 0.0% | 99.9% |  |
| YIELD_VALUE | 600,000 | 0.0% | 100.0% |  |
| CALL_BUILTIN_O | 423,180 | 0.0% | 100.0% |  |
| FOR_ITER_RANGE | 265,860 | 0.0% | 100.0% |  |
| GET_ITER | 265,560 | 0.0% | 100.0% |  |
| LOAD_ATTR_MODULE | 180,800 | 0.0% | 100.0% |  |
| LOAD_GLOBAL_MODULE | 143,480 | 0.0% | 100.0% |  |
| LIST_APPEND | 134,880 | 0.0% | 100.0% |  |
| PUSH_NULL | 121,560 | 0.0% | 100.0% |  |
| EXTENDED_ARG | 60,000 | 0.0% | 100.0% |  |
| CALL | 15,540 | 0.0% | 100.0% |  |
| STORE_SUBSCR_LIST_INT | 11,400 | 0.0% | 100.0% |  |
| FOR_ITER | 6,100 | 0.0% | 100.0% |  |
| STORE_SLICE | 6,060 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 1,340 | 0.0% | 100.0% |  |
| BUILD_LIST | 1,200 | 0.0% | 100.0% |  |
| LOAD_ATTR | 940 | 0.0% | 100.0% |  |
| LOAD_DEREF | 900 | 0.0% | 100.0% |  |
| CALL_FUNCTION_EX | 600 | 0.0% | 100.0% |  |
| STORE_ATTR | 540 | 0.0% | 100.0% |  |
| NOP | 300 | 0.0% | 100.0% |  |
| LIST_EXTEND | 300 | 0.0% | 100.0% |  |
| COPY_FREE_VARS | 300 | 0.0% | 100.0% |  |
| CALL_INTRINSIC_1 | 300 | 0.0% | 100.0% |  |
| POP_JUMP_IF_NONE | 180 | 0.0% | 100.0% |  |
| LOAD_FAST_AND_CLEAR | 180 | 0.0% | 100.0% |  |
| EXIT_INIT_CHECK | 180 | 0.0% | 100.0% |  |
| CALL_ALLOC_AND_ENTER_INIT | 180 | 0.0% | 100.0% |  |
| STORE_FAST_LOAD_FAST | 60 | 0.0% | 100.0% |  |
| RETURN_GENERATOR | 60 | 0.0% | 100.0% |  |
| END_FOR | 60 | 0.0% | 100.0% |  |
| BINARY_SLICE | 60 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 190,214,060 | 4.3% | 4.3% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 170,070,780 | 3.8% | 8.1% |
| POP_JUMP_IF_FALSE LOAD_FAST | 165,556,080 | 3.7% | 11.8% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 120,838,440 | 2.7% | 14.6% |
| BINARY_SUBSCR_GETITEM RESUME_CHECK | 88,538,340 | 2.0% | 16.6% |
| LOAD_CONST BINARY_OP_ADD_INT | 77,894,620 | 1.8% | 18.3% |
| LOAD_CONST LOAD_FAST | 75,441,120 | 1.7% | 20.0% |
| SWAP SWAP | 75,363,000 | 1.7% | 21.7% |
| SWAP STORE_SUBSCR | 75,363,000 | 1.7% | 23.4% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 73,214,760 | 1.6% | 25.1% |
| LOAD_FAST_LOAD_FAST LOAD_CONST | 73,105,980 | 1.6% | 26.7% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 73,060,620 | 1.6% | 28.3% |
| LOAD_FAST LOAD_CONST | 71,121,960 | 1.6% | 29.9% |
| COPY COPY | 69,285,000 | 1.6% | 31.5% |
| COPY BINARY_SUBSCR | 69,285,000 | 1.6% | 33.1% |
| SWAP COPY | 69,148,800 | 1.6% | 34.6% |
| POP_JUMP_IF_FALSE JUMP_FORWARD | 69,148,800 | 1.6% | 36.2% |
| LOAD_FAST SWAP | 69,148,800 | 1.6% | 37.7% |
| LOAD_ATTR_INSTANCE_VALUE COMPARE_OP_INT | 69,148,800 | 1.6% | 39.3% |
| COPY COMPARE_OP_INT | 69,148,800 | 1.6% | 40.9% |
| BINARY_SUBSCR LOAD_FAST | 61,860,000 | 1.4% | 42.3% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 60,337,980 | 1.4% | 43.6% |
| LOAD_GLOBAL_BUILTIN CALL_ISINSTANCE | 60,337,740 | 1.4% | 45.0% |
| LOAD_FAST LOAD_GLOBAL_BUILTIN | 60,337,740 | 1.4% | 46.3% |
| CALL_ISINSTANCE TO_BOOL_BOOL | 60,337,740 | 1.4% | 47.7% |
| LOAD_FAST BINARY_SUBSCR_LIST_INT | 59,726,340 | 1.3% | 49.0% |
| BINARY_SUBSCR_LIST_INT RETURN_VALUE | 59,726,340 | 1.3% | 50.4% |
| RETURN_VALUE LOAD_FAST | 59,714,940 | 1.3% | 51.7% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 58,928,580 | 1.3% | 53.0% |
| STORE_SUBSCR ENTER_EXECUTOR | 57,503,520 | 1.3% | 54.3% |
| STORE_SUBSCR LOAD_FAST_LOAD_FAST | 55,439,400 | 1.2% | 55.6% |
| LOAD_FAST BINARY_OP_ADD_FLOAT | 55,362,000 | 1.2% | 56.8% |
| BINARY_OP_ADD_FLOAT SWAP | 55,362,000 | 1.2% | 58.1% |
| LOAD_FAST_LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 53,671,080 | 1.2% | 59.3% |
| BINARY_SUBSCR LOAD_FAST_LOAD_FAST | 46,002,240 | 1.0% | 60.3% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 41,190,420 | 0.9% | 61.3% |
| RESUME_CHECK LOAD_FAST | 41,186,940 | 0.9% | 62.2% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 41,174,700 | 0.9% | 63.1% |
| LOAD_FAST BINARY_SUBSCR | 39,716,940 | 0.9% | 64.0% |
| LOAD_FAST_LOAD_FAST BINARY_SUBSCR_GETITEM | 39,443,220 | 0.9% | 64.9% |
| BINARY_OP_SUBTRACT_FLOAT LOAD_FAST_LOAD_FAST | 36,596,400 | 0.8% | 65.7% |
| LOAD_FAST BINARY_OP_SUBTRACT_FLOAT | 36,542,600 | 0.8% | 66.5% |
| JUMP_FORWARD LOAD_FAST_LOAD_FAST | 36,071,160 | 0.8% | 67.4% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST_STORE_FAST | 35,180,400 | 0.8% | 68.1% |
| LOAD_FAST BINARY_OP_ADD_INT | 34,793,460 | 0.8% | 68.9% |
| LOAD_FAST_LOAD_FAST CALL_PY_EXACT_ARGS | 34,583,500 | 0.8% | 69.7% |
| RESUME_CHECK LOAD_CONST | 34,577,520 | 0.8% | 70.5% |
| LOAD_FAST UNPACK_SEQUENCE_TWO_TUPLE | 34,574,400 | 0.8% | 71.3% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST_LOAD_FAST | 34,574,400 | 0.8% | 72.0% |
| LOAD_ATTR_INSTANCE_VALUE BINARY_OP_MULTIPLY_INT | 34,574,400 | 0.8% | 72.8% |
| JUMP_FORWARD LOAD_CONST | 34,574,400 | 0.8% | 73.6% |
| BINARY_OP_MULTIPLY_INT LOAD_FAST | 34,574,400 | 0.8% | 74.4% |
| BINARY_OP_ADD_INT RETURN_VALUE | 34,574,400 | 0.8% | 75.2% |
| LOAD_CONST BINARY_OP_SUBTRACT_INT | 29,729,940 | 0.7% | 75.8% |
| STORE_FAST_STORE_FAST LOAD_FAST | 29,412,000 | 0.7% | 76.5% |
| RETURN_VALUE BINARY_SUBSCR | 28,812,000 | 0.6% | 77.1% |
| BINARY_SUBSCR RETURN_VALUE | 28,812,000 | 0.6% | 77.8% |
| STORE_FAST LOAD_FAST | 28,045,620 | 0.6% | 78.4% |
| ENTER_EXECUTOR BINARY_SUBSCR_GETITEM | 26,045,340 | 0.6% | 79.0% |
| BINARY_OP_MULTIPLY_FLOAT BINARY_OP_SUBTRACT_FLOAT | 25,941,000 | 0.6% | 79.6% |
| LOAD_FAST_LOAD_FAST BINARY_SUBSCR | 25,476,480 | 0.6% | 80.2% |
| LOAD_CONST COMPARE_OP_INT | 25,455,000 | 0.6% | 80.7% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 25,446,200 | 0.6% | 81.3% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST | 25,445,940 | 0.6% | 81.9% |
| LOAD_FAST BINARY_OP_MULTIPLY_FLOAT | 24,840,000 | 0.6% | 82.4% |
| BINARY_OP_SUBTRACT_INT STORE_FAST | 24,765,000 | 0.6% | 83.0% |
| BINARY_OP_ADD_INT STORE_SUBSCR | 24,699,120 | 0.6% | 83.6% |
| LOAD_FAST_LOAD_FAST COPY | 24,645,000 | 0.6% | 84.1% |
| ENTER_EXECUTOR LOAD_FAST | 24,642,000 | 0.6% | 84.7% |
| BINARY_OP_ADD_INT COPY | 24,642,000 | 0.6% | 85.2% |
| LOAD_FAST LOAD_FAST | 24,420,000 | 0.5% | 85.8% |
| LOAD_FAST BUILD_TUPLE | 23,649,600 | 0.5% | 86.3% |
| BUILD_TUPLE BINARY_SUBSCR_GETITEM | 23,049,780 | 0.5% | 86.8% |
| LOAD_FAST COPY | 19,998,000 | 0.5% | 87.3% |
| BINARY_SUBSCR BINARY_OP_MULTIPLY_FLOAT | 19,701,060 | 0.4% | 87.7% |
| BINARY_OP_SUBTRACT_FLOAT SWAP | 19,701,000 | 0.4% | 88.2% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 19,018,620 | 0.4% | 88.6% |
| BINARY_OP_MULTIPLY_FLOAT BINARY_OP_ADD_FLOAT | 17,894,460 | 0.4% | 89.0% |
| BINARY_OP_ADD_FLOAT LOAD_FAST_LOAD_FAST | 17,344,260 | 0.4% | 89.4% |
| RETURN_VALUE BINARY_OP_ADD_FLOAT | 17,287,200 | 0.4% | 89.8% |
| ENTER_EXECUTOR LOAD_FAST_LOAD_FAST | 15,462,960 | 0.3% | 90.1% |
| LOAD_FAST STORE_SUBSCR | 13,691,940 | 0.3% | 90.4% |
| LOAD_FAST CALL_BUILTIN_CLASS | 12,936,420 | 0.3% | 90.7% |
| BINARY_OP_SUBTRACT_FLOAT STORE_FAST | 12,786,120 | 0.3% | 91.0% |
| CALL_BUILTIN_CLASS BINARY_OP_MULTIPLY_FLOAT | 12,782,880 | 0.3% | 91.3% |
| LOAD_FAST LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 12,726,180 | 0.3% | 91.6% |
| STORE_SUBSCR LOAD_FAST | 12,722,940 | 0.3% | 91.9% |
| BINARY_OP_MULTIPLY_FLOAT RETURN_VALUE | 12,722,940 | 0.3% | 92.2% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES LOAD_GLOBAL_BUILTIN | 12,722,880 | 0.3% | 92.4% |
| LOAD_ATTR_INSTANCE_VALUE TO_BOOL_BOOL | 12,722,880 | 0.3% | 92.7% |
| BINARY_SUBSCR STORE_FAST | 12,276,060 | 0.3% | 93.0% |
| BINARY_OP_ADD_INT BINARY_SUBSCR | 12,276,060 | 0.3% | 93.3% |
| BINARY_OP_MULTIPLY_FLOAT LOAD_FAST | 12,216,000 | 0.3% | 93.6% |
| LOAD_FAST_LOAD_FAST BINARY_OP_MULTIPLY_FLOAT | 12,108,000 | 0.3% | 93.8% |
| RETURN_VALUE STORE_FAST | 12,006,300 | 0.3% | 94.1% |
| POP_JUMP_IF_FALSE LOAD_FAST_LOAD_FAST | 11,927,580 | 0.3% | 94.4% |
| BINARY_OP_ADD_INT STORE_FAST | 10,923,840 | 0.2% | 94.6% |
| STORE_FAST ENTER_EXECUTOR | 10,879,140 | 0.2% | 94.9% |
| BINARY_OP STORE_FAST | 9,533,460 | 0.2% | 95.1% |
| ENTER_EXECUTOR ENTER_EXECUTOR | 7,470,020 | 0.2% | 95.2% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### BINARY_SLICE

<details>
<summary> Successors and predecessors for BINARY_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60 | 100.0% |


</details>

### STORE_SLICE

<details>
<summary> Successors and predecessors for STORE_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 6,060 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 6,000 | 99.0% |
| LOAD_FAST | 60 | 1.0% |


</details>

### BINARY_SUBSCR

<details>
<summary> Successors and predecessors for BINARY_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY | 69,285,000 | 39.5% |
| LOAD_FAST | 39,716,940 | 22.6% |
| RETURN_VALUE | 28,812,000 | 16.4% |
| LOAD_FAST_LOAD_FAST | 25,476,480 | 14.5% |
| BINARY_OP_ADD_INT | 12,276,060 | 7.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 61,860,000 | 35.2% |
| LOAD_FAST_LOAD_FAST | 46,002,240 | 26.2% |
| RETURN_VALUE | 28,812,000 | 16.4% |
| BINARY_OP_MULTIPLY_FLOAT | 19,701,060 | 11.2% |
| STORE_FAST | 12,276,060 | 7.0% |


</details>

### EXIT_INIT_CHECK

<details>
<summary> Successors and predecessors for EXIT_INIT_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 180 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 180 | 100.0% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_CLASS | 265,140 | 99.8% |
| LOAD_FAST | 300 | 0.1% |
| RETURN_GENERATOR | 60 | 0.0% |
| CALL | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_RANGE | 265,260 | 99.9% |
| LOAD_FAST_AND_CLEAR | 180 | 0.1% |
| FOR_ITER_GEN | 60 | 0.0% |
| FOR_ITER | 60 | 0.0% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 300 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_DEREF | 300 | 100.0% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 600,000 | 97.0% |
| RETURN_CONST | 18,420 | 3.0% |
| CALL | 300 | 0.0% |
| RETURN_VALUE | 60 | 0.0% |
| FOR_ITER_GEN | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 603,000 | 97.4% |
| LOAD_CONST | 9,180 | 1.5% |
| RETURN_CONST | 3,060 | 0.5% |
| LOAD_GLOBAL_MODULE | 3,040 | 0.5% |
| NOP | 300 | 0.0% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 120,800 | 99.4% |
| LOAD_DEREF | 600 | 0.5% |
| LOAD_ATTR | 100 | 0.1% |
| LOAD_FAST | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 120,600 | 99.2% |
| CALL | 900 | 0.7% |
| LOAD_FAST_LOAD_FAST | 60 | 0.0% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_LIST_INT | 59,726,340 | 44.0% |
| BINARY_OP_ADD_INT | 34,574,400 | 25.5% |
| BINARY_SUBSCR | 28,812,000 | 21.2% |
| BINARY_OP_MULTIPLY_FLOAT | 12,722,940 | 9.4% |
| LOAD_FAST | 6,120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 59,714,940 | 44.0% |
| BINARY_SUBSCR | 28,812,000 | 21.2% |
| BINARY_OP_ADD_FLOAT | 17,287,200 | 12.7% |
| STORE_FAST | 12,006,300 | 8.8% |
| LOAD_FAST_LOAD_FAST | 6,368,100 | 4.7% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 75,363,000 | 56.8% |
| BINARY_OP_ADD_INT | 24,699,120 | 18.6% |
| LOAD_FAST | 13,691,940 | 10.3% |
| BUILD_TUPLE | 6,362,400 | 4.8% |
| LOAD_FAST_LOAD_FAST | 6,149,400 | 4.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 57,503,520 | 43.3% |
| LOAD_FAST_LOAD_FAST | 55,439,400 | 41.8% |
| LOAD_FAST | 12,722,940 | 9.6% |
| RETURN_CONST | 6,362,400 | 4.8% |
| JUMP_BACKWARD | 600,000 | 0.5% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 6,367,980 | 66.1% |
| LOAD_CONST | 3,159,520 | 32.8% |
| BINARY_OP_MULTIPLY_FLOAT | 60,000 | 0.6% |
| LOAD_FAST | 27,540 | 0.3% |
| BINARY_OP | 10,400 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 9,533,460 | 98.9% |
| CALL_BUILTIN_O | 60,000 | 0.6% |
| LIST_APPEND | 12,000 | 0.1% |
| BINARY_OP | 10,400 | 0.1% |
| BINARY_OP_ADD_FLOAT | 6,120 | 0.1% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 720 | 60.0% |
| LOAD_FAST | 300 | 25.0% |
| SWAP | 180 | 15.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 720 | 60.0% |
| LOAD_DEREF | 300 | 25.0% |
| SWAP | 180 | 15.0% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 11,880 | 76.4% |
| PUSH_NULL | 900 | 5.8% |
| CALL | 760 | 4.9% |
| BUILD_LIST | 720 | 4.6% |
| LOAD_FAST | 500 | 3.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,660 | 81.5% |
| CALL | 760 | 4.9% |
| STORE_FAST | 720 | 4.6% |
| CALL_BUILTIN_CLASS | 320 | 2.1% |
| POP_TOP | 300 | 1.9% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 300 | 50.0% |
| CALL_INTRINSIC_1 | 300 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 300 | 50.0% |
| COPY_FREE_VARS | 300 | 50.0% |


</details>

### CALL_INTRINSIC_1

<details>
<summary> Successors and predecessors for CALL_INTRINSIC_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LIST_EXTEND | 300 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 300 | 100.0% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 6,606,180 | 100.0% |
| COMPARE_OP | 1,640 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 6,606,120 | 100.0% |
| COMPARE_OP | 1,640 | 0.0% |
| COMPARE_OP_INT | 60 | 0.0% |


</details>

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY | 69,285,000 | 33.4% |
| SWAP | 69,148,800 | 33.3% |
| LOAD_FAST_LOAD_FAST | 24,645,000 | 11.9% |
| BINARY_OP_ADD_INT | 24,642,000 | 11.9% |
| LOAD_FAST | 19,998,000 | 9.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 69,285,000 | 33.4% |
| BINARY_SUBSCR | 69,285,000 | 33.4% |
| COMPARE_OP_INT | 69,148,800 | 33.3% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 300 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 300 | 100.0% |


</details>

### ENTER_EXECUTOR

<details>
<summary> Successors and predecessors for ENTER_EXECUTOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_SUBSCR | 57,503,520 | 72.1% |
| STORE_FAST | 10,879,140 | 13.6% |
| ENTER_EXECUTOR | 7,470,020 | 9.4% |
| POP_JUMP_IF_TRUE | 1,555,920 | 2.0% |
| POP_JUMP_IF_FALSE | 1,536,000 | 1.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_GETITEM | 26,045,340 | 32.7% |
| LOAD_FAST | 24,642,000 | 30.9% |
| LOAD_FAST_LOAD_FAST | 15,462,960 | 19.4% |
| ENTER_EXECUTOR | 7,470,020 | 9.4% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 3,064,560 | 3.8% |


</details>

### EXTENDED_ARG

<details>
<summary> Successors and predecessors for EXTENDED_ARG </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 54,000 | 90.0% |
| COMPARE_OP_INT | 6,000 | 10.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 54,000 | 90.0% |
| POP_JUMP_IF_FALSE | 6,000 | 10.0% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 6,000 | 98.4% |
| GET_ITER | 60 | 1.0% |
| FOR_ITER | 40 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 6,000 | 98.4% |
| RETURN_CONST | 60 | 1.0% |
| FOR_ITER | 40 | 0.7% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_SUBSCR | 600,000 | 98.9% |
| STORE_SLICE | 6,000 | 1.0% |
| ENTER_EXECUTOR | 220 | 0.0% |
| POP_TOP | 180 | 0.0% |
| POP_JUMP_IF_TRUE | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_GEN | 600,000 | 98.9% |
| FOR_ITER | 6,000 | 1.0% |
| FOR_ITER_RANGE | 420 | 0.1% |
| ENTER_EXECUTOR | 40 | 0.0% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 69,148,800 | 97.9% |
| STORE_FAST | 1,496,760 | 2.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 36,071,160 | 51.1% |
| LOAD_CONST | 34,574,400 | 48.9% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 122,880 | 91.1% |
| BINARY_OP | 12,000 | 8.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 134,880 | 100.0% |


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_DEREF | 300 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 300 | 100.0% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 340 | 36.2% |
| LOAD_GLOBAL_MODULE | 300 | 31.9% |
| LOAD_FAST_LOAD_FAST | 180 | 19.1% |
| LOAD_GLOBAL | 100 | 10.6% |
| RETURN_VALUE | 20 | 2.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 300 | 31.9% |
| LOAD_ATTR_MODULE | 300 | 31.9% |
| LOAD_ATTR_METHOD_WITH_VALUES | 140 | 14.9% |
| PUSH_NULL | 100 | 10.6% |
| LOAD_ATTR_INSTANCE_VALUE | 100 | 10.6% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 73,105,980 | 32.2% |
| LOAD_FAST | 71,121,960 | 31.3% |
| RESUME_CHECK | 34,577,520 | 15.2% |
| JUMP_FORWARD | 34,574,400 | 15.2% |
| BINARY_OP_ADD_FLOAT | 6,000,000 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 77,894,620 | 34.3% |
| LOAD_FAST | 75,441,120 | 33.2% |
| BINARY_OP_SUBTRACT_INT | 29,729,940 | 13.1% |
| COMPARE_OP_INT | 25,455,000 | 11.2% |
| COMPARE_OP | 6,606,180 | 2.9% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 300 | 33.3% |
| NOP | 300 | 33.3% |
| BUILD_LIST | 300 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 600 | 66.7% |
| LIST_EXTEND | 300 | 33.3% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 165,556,080 | 20.1% |
| LOAD_ATTR_INSTANCE_VALUE | 120,838,440 | 14.6% |
| LOAD_CONST | 75,441,120 | 9.1% |
| LOAD_GLOBAL_BUILTIN | 73,214,760 | 8.9% |
| BINARY_SUBSCR | 61,860,000 | 7.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 190,214,060 | 23.0% |
| LOAD_CONST | 71,121,960 | 8.6% |
| SWAP | 69,148,800 | 8.4% |
| LOAD_GLOBAL_BUILTIN | 60,337,740 | 7.3% |
| BINARY_SUBSCR_LIST_INT | 59,726,340 | 7.2% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 180 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 180 | 100.0% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 58,928,580 | 17.8% |
| STORE_SUBSCR | 55,439,400 | 16.8% |
| BINARY_SUBSCR | 46,002,240 | 13.9% |
| BINARY_OP_SUBTRACT_FLOAT | 36,596,400 | 11.1% |
| JUMP_FORWARD | 36,071,160 | 10.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 73,105,980 | 22.1% |
| LOAD_ATTR_INSTANCE_VALUE | 53,671,080 | 16.2% |
| BINARY_SUBSCR_GETITEM | 39,443,220 | 11.9% |
| CALL_PY_EXACT_ARGS | 34,583,500 | 10.5% |
| BINARY_SUBSCR | 25,476,480 | 7.7% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 540 | 40.3% |
| RESUME_CHECK | 220 | 16.4% |
| RETURN_VALUE | 200 | 14.9% |
| STORE_ATTR_INSTANCE_VALUE | 140 | 10.4% |
| FOR_ITER_RANGE | 80 | 6.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 760 | 56.7% |
| LOAD_GLOBAL_BUILTIN | 480 | 35.8% |
| LOAD_ATTR | 100 | 7.5% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 170,070,780 | 68.1% |
| TO_BOOL_BOOL | 73,060,620 | 29.3% |
| COMPARE_OP | 6,606,120 | 2.6% |
| EXTENDED_ARG | 6,000 | 0.0% |
| ENTER_EXECUTOR | 2,940 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 165,556,080 | 66.3% |
| JUMP_FORWARD | 69,148,800 | 27.7% |
| LOAD_FAST_LOAD_FAST | 11,927,580 | 4.8% |
| ENTER_EXECUTOR | 1,536,000 | 0.6% |
| LOAD_CONST | 1,508,940 | 0.6% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 180 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 180 | 100.0% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_FLOAT | 6,297,000 | 99.9% |
| COMPARE_OP_INT | 6,000 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,741,080 | 75.2% |
| ENTER_EXECUTOR | 1,555,920 | 24.7% |
| LOAD_GLOBAL_BUILTIN | 5,940 | 0.1% |
| JUMP_BACKWARD | 60 | 0.0% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_SUBSCR | 6,362,400 | 99.5% |
| STORE_SUBSCR_LIST_INT | 11,400 | 0.2% |
| ENTER_EXECUTOR | 9,120 | 0.1% |
| POP_JUMP_IF_FALSE | 6,000 | 0.1% |
| POP_TOP | 3,060 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 6,373,980 | 99.7% |
| POP_TOP | 18,420 | 0.3% |
| EXIT_INIT_CHECK | 180 | 0.0% |
| END_FOR | 60 | 0.0% |


</details>

### STORE_ATTR

<details>
<summary> Successors and predecessors for STORE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 440 | 81.5% |
| LOAD_FAST_LOAD_FAST | 100 | 18.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 540 | 100.0% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_SUBTRACT_INT | 24,765,000 | 24.8% |
| BINARY_OP_SUBTRACT_FLOAT | 12,786,120 | 12.8% |
| BINARY_SUBSCR | 12,276,060 | 12.3% |
| RETURN_VALUE | 12,006,300 | 12.0% |
| BINARY_OP_ADD_INT | 10,923,840 | 10.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 58,928,580 | 59.0% |
| LOAD_FAST | 28,045,620 | 28.1% |
| ENTER_EXECUTOR | 10,879,140 | 10.9% |
| JUMP_FORWARD | 1,496,760 | 1.5% |
| LOAD_CONST | 318,540 | 0.3% |


</details>

### STORE_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_RANGE | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 60 | 100.0% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 35,180,400 | 84.2% |
| LOAD_ATTR_INSTANCE_VALUE | 6,600,180 | 15.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 29,412,000 | 70.4% |
| STORE_FAST | 6,600,120 | 15.8% |
| LOAD_FAST_LOAD_FAST | 5,768,400 | 13.8% |
| LOAD_GLOBAL_BUILTIN | 40 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 75,363,000 | 34.3% |
| LOAD_FAST | 69,148,800 | 31.4% |
| BINARY_OP_ADD_FLOAT | 55,362,000 | 25.2% |
| BINARY_OP_SUBTRACT_FLOAT | 19,701,000 | 9.0% |
| BINARY_OP_MULTIPLY_FLOAT | 300,000 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 75,363,000 | 34.3% |
| STORE_SUBSCR | 75,363,000 | 34.3% |
| COPY | 69,148,800 | 31.4% |
| LOAD_FAST_LOAD_FAST | 5,700 | 0.0% |
| STORE_FAST | 180 | 0.0% |


</details>

### BINARY_OP_ADD_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 55,362,000 | 61.1% |
| BINARY_OP_MULTIPLY_FLOAT | 17,894,460 | 19.8% |
| RETURN_VALUE | 17,287,200 | 19.1% |
| BINARY_OP | 6,120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 55,362,000 | 61.1% |
| LOAD_FAST_LOAD_FAST | 17,344,260 | 19.2% |
| STORE_FAST | 6,078,060 | 6.7% |
| LOAD_CONST | 6,000,000 | 6.6% |
| BINARY_OP_MULTIPLY_FLOAT | 5,762,400 | 6.4% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 77,894,620 | 65.5% |
| LOAD_FAST | 34,793,460 | 29.3% |
| LOAD_FAST_LOAD_FAST | 6,198,060 | 5.2% |
| BINARY_OP | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 34,574,400 | 29.1% |
| STORE_SUBSCR | 24,699,120 | 20.8% |
| COPY | 24,642,000 | 20.7% |
| BINARY_SUBSCR | 12,276,060 | 10.3% |
| STORE_FAST | 10,923,840 | 9.2% |


</details>

### BINARY_OP_MULTIPLY_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 24,840,000 | 30.7% |
| BINARY_SUBSCR | 19,701,060 | 24.3% |
| CALL_BUILTIN_CLASS | 12,782,880 | 15.8% |
| LOAD_FAST_LOAD_FAST | 12,108,000 | 14.9% |
| RETURN_VALUE | 5,762,400 | 7.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_SUBTRACT_FLOAT | 25,941,000 | 32.0% |
| BINARY_OP_ADD_FLOAT | 17,894,460 | 22.1% |
| RETURN_VALUE | 12,722,940 | 15.7% |
| LOAD_FAST | 12,216,000 | 15.1% |
| LOAD_FAST_LOAD_FAST | 6,000,180 | 7.4% |


</details>

### BINARY_OP_MULTIPLY_INT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 34,574,400 | 98.7% |
| LOAD_FAST | 174,040 | 0.5% |
| BINARY_OP_ADD_INT | 168,000 | 0.5% |
| LOAD_CONST | 63,060 | 0.2% |
| LOAD_FAST_LOAD_FAST | 57,320 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 34,574,400 | 98.7% |
| STORE_FAST | 291,360 | 0.8% |
| CALL_BUILTIN_CLASS | 114,000 | 0.3% |
| LOAD_FAST_LOAD_FAST | 57,060 | 0.2% |
| BINARY_OP | 60 | 0.0% |


</details>

### BINARY_OP_SUBTRACT_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 36,542,600 | 52.9% |
| BINARY_OP_MULTIPLY_FLOAT | 25,941,000 | 37.6% |
| BINARY_SUBSCR | 6,600,120 | 9.6% |
| BINARY_OP | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 36,596,400 | 53.0% |
| SWAP | 19,701,000 | 28.5% |
| STORE_FAST | 12,786,120 | 18.5% |
| RETURN_VALUE | 300 | 0.0% |


</details>

### BINARY_OP_SUBTRACT_INT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 29,729,940 | 97.3% |
| LOAD_FAST_LOAD_FAST | 810,000 | 2.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 24,765,000 | 81.1% |
| LOAD_FAST | 5,762,400 | 18.9% |
| COMPARE_OP_INT | 12,000 | 0.0% |
| CALL_BUILTIN_CLASS | 360 | 0.0% |
| BUILD_TUPLE | 180 | 0.0% |


</details>

### CALL_ALLOC_AND_ENTER_INIT

<details>
<summary> Successors and predecessors for CALL_ALLOC_AND_ENTER_INIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 120 | 66.7% |
| CALL | 60 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 180 | 100.0% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,936,420 | 99.1% |
| BINARY_OP_MULTIPLY_INT | 114,000 | 0.9% |
| BINARY_OP_SUBTRACT_INT | 360 | 0.0% |
| CALL | 320 | 0.0% |
| LOAD_CONST | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_MULTIPLY_FLOAT | 12,782,880 | 97.9% |
| GET_ITER | 265,140 | 2.0% |
| BINARY_OP | 3,000 | 0.0% |
| STORE_FAST | 300 | 0.0% |
| LOAD_FAST | 60 | 0.0% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR | 303,000 | 71.6% |
| LOAD_FAST | 60,120 | 14.2% |
| BINARY_OP | 60,000 | 14.2% |
| CALL | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 423,180 | 100.0% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 34,583,500 | 84.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 6,600,160 | 16.0% |
| LOAD_FAST | 3,460 | 0.0% |
| LOAD_CONST | 3,060 | 0.0% |
| CALL | 300 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 41,190,420 | 100.0% |
| RETURN_GENERATOR | 60 | 0.0% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 69,148,800 | 40.7% |
| COPY | 69,148,800 | 40.7% |
| LOAD_CONST | 25,455,000 | 15.0% |
| LOAD_FAST_LOAD_FAST | 6,312,120 | 3.7% |
| BINARY_OP_SUBTRACT_INT | 12,000 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 170,070,780 | 100.0% |
| POP_JUMP_IF_TRUE | 6,000 | 0.0% |
| EXTENDED_ARG | 6,000 | 0.0% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 265,260 | 99.8% |
| JUMP_BACKWARD | 420 | 0.2% |
| SWAP | 180 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 259,440 | 97.6% |
| LOAD_FAST | 6,000 | 2.3% |
| LOAD_GLOBAL_MODULE | 160 | 0.1% |
| LOAD_GLOBAL | 80 | 0.0% |
| STORE_FAST_LOAD_FAST | 60 | 0.0% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 190,214,060 | 78.0% |
| LOAD_FAST_LOAD_FAST | 53,671,080 | 22.0% |
| LOAD_ATTR | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 120,838,440 | 49.5% |
| COMPARE_OP_INT | 69,148,800 | 28.4% |
| BINARY_OP_MULTIPLY_INT | 34,574,400 | 14.2% |
| TO_BOOL_BOOL | 12,722,880 | 5.2% |
| STORE_FAST_STORE_FAST | 6,600,180 | 2.7% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 41,174,700 | 100.0% |
| LOAD_ATTR | 140 | 0.0% |
| STORE_FAST_LOAD_FAST | 60 | 0.0% |
| RETURN_VALUE | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 34,574,400 | 84.0% |
| CALL_PY_EXACT_ARGS | 6,600,160 | 16.0% |
| LOAD_FAST | 300 | 0.0% |
| LOAD_GLOBAL_MODULE | 40 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 126,500 | 70.0% |
| ENTER_EXECUTOR | 54,000 | 29.9% |
| LOAD_ATTR | 300 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 120,800 | 66.8% |
| BINARY_OP_MULTIPLY_FLOAT | 60,000 | 33.2% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,726,180 | 66.6% |
| LOAD_FAST_LOAD_FAST | 3,306,120 | 17.3% |
| ENTER_EXECUTOR | 3,064,560 | 16.0% |
| LOAD_ATTR | 300 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 12,722,880 | 66.6% |
| BINARY_OP | 6,367,980 | 33.3% |
| LOAD_FAST | 3,060 | 0.0% |
| LOAD_CONST | 3,060 | 0.0% |
| CALL | 180 | 0.0% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 60,337,980 | 45.1% |
| LOAD_FAST | 60,337,740 | 45.1% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 12,722,880 | 9.5% |
| STORE_FAST | 147,800 | 0.1% |
| ENTER_EXECUTOR | 117,040 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 73,214,760 | 54.7% |
| CALL_ISINSTANCE | 60,337,740 | 45.1% |
| LOAD_CONST | 174,540 | 0.1% |
| LOAD_FAST_LOAD_FAST | 6,300 | 0.0% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 123,940 | 86.4% |
| POP_JUMP_IF_FALSE | 9,060 | 6.3% |
| BINARY_OP | 6,000 | 4.2% |
| POP_TOP | 3,040 | 2.1% |
| LOAD_GLOBAL | 760 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 126,500 | 88.2% |
| LOAD_FAST_LOAD_FAST | 12,420 | 8.7% |
| LOAD_FAST | 3,180 | 2.2% |
| LOAD_CONST | 1,080 | 0.8% |
| LOAD_ATTR | 300 | 0.2% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_GETITEM | 88,538,340 | 64.8% |
| CALL_PY_EXACT_ARGS | 41,190,420 | 30.1% |
| CACHE | 6,373,980 | 4.7% |
| FOR_ITER_GEN | 600,000 | 0.4% |
| COPY_FREE_VARS | 300 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 60,337,980 | 44.1% |
| LOAD_FAST | 41,186,940 | 30.1% |
| LOAD_CONST | 34,577,520 | 25.3% |
| POP_TOP | 600,000 | 0.4% |
| LOAD_FAST_LOAD_FAST | 360 | 0.0% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 25,446,200 | 100.0% |
| LOAD_FAST | 1,000 | 0.0% |
| STORE_ATTR | 540 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 25,445,940 | 100.0% |
| LOAD_CONST | 720 | 0.0% |
| RETURN_CONST | 360 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 360 | 0.0% |
| LOAD_FAST_LOAD_FAST | 180 | 0.0% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 60,337,740 | 82.6% |
| LOAD_ATTR_INSTANCE_VALUE | 12,722,880 | 17.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 73,060,620 | 100.0% |


</details>

### COMPARE_OP_FLOAT

<details>
<summary> Successors and predecessors for COMPARE_OP_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 6,000,000 | 95.3% |
| LOAD_FAST_LOAD_FAST | 297,000 | 4.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 6,297,000 | 100.0% |


</details>

### CACHE

<details>
<summary> Successors and predecessors for CACHE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 6,373,980 | 100.0% |


</details>

### END_FOR

<details>
<summary> Successors and predecessors for END_FOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60 | 100.0% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 6,373,980 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|


</details>

### RETURN_GENERATOR

<details>
<summary> Successors and predecessors for RETURN_GENERATOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 60 | 100.0% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 23,649,600 | 80.4% |
| BINARY_OP_ADD_INT | 5,762,400 | 19.6% |
| BINARY_OP_SUBTRACT_INT | 180 | 0.0% |
| LOAD_FAST_LOAD_FAST | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_GETITEM | 23,049,780 | 78.4% |
| STORE_SUBSCR | 6,362,400 | 21.6% |
| YIELD_VALUE | 60 | 0.0% |


</details>

### YIELD_VALUE

<details>
<summary> Successors and predecessors for YIELD_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 599,940 | 100.0% |
| BUILD_TUPLE | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 600,000 | 100.0% |


</details>

### BINARY_SUBSCR_GETITEM

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_GETITEM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 39,443,220 | 44.5% |
| ENTER_EXECUTOR | 26,045,340 | 29.4% |
| BUILD_TUPLE | 23,049,780 | 26.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 88,538,340 | 100.0% |


</details>

### BINARY_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 59,726,340 | 99.0% |
| BINARY_SUBSCR_TUPLE_INT | 600,000 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 59,726,340 | 99.0% |
| LOAD_FAST | 600,000 | 1.0% |


</details>

### BINARY_SUBSCR_TUPLE_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_TUPLE_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,200,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_SUBSCR | 600,000 | 50.0% |
| BINARY_SUBSCR_LIST_INT | 600,000 | 50.0% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 60,337,740 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 60,337,740 | 100.0% |


</details>

### FOR_ITER_GEN

<details>
<summary> Successors and predecessors for FOR_ITER_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 600,000 | 100.0% |
| GET_ITER | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 600,000 | 100.0% |
| POP_TOP | 60 | 0.0% |


</details>

### STORE_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 11,400 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 11,400 | 100.0% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 34,574,400 | 98.3% |
| YIELD_VALUE | 600,000 | 1.7% |
| FOR_ITER | 6,000 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 35,180,400 | 100.0% |


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
| specialization.deferred |    175566540 | 53.9% |
|          hit |    150064680 | 46.1% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 0 | 0.0% |
| Failure | 42,940 | 100.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| array int | 42,940 | 100.0% |


</details>

### STORE_SUBSCR

<details>
<summary> specialization stats for STORE_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |    132628320 | 100.0% |
|          hit |        11400 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 0 | 0.0% |
| Failure | 32,660 | 100.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| array int | 31,040 | 95.0% |
| py simple | 1,620 | 5.0% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |     73060620 | 100.0% |


</details>

### BINARY_OP

<details>
<summary> specialization stats for BINARY_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      9636300 | 1.0% |
|          hit |    973678200 | 99.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 200 | 4.5% |
| Failure | 4,280 | 95.5% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| add different types | 1,660 | 38.8% |
| rshift | 780 | 18.2% |
| multiply different types | 640 | 15.0% |
| remainder | 420 | 9.8% |
| true divide other | 400 | 9.3% |
| true divide float | 120 | 2.8% |
| lshift | 120 | 2.8% |
| floor divide | 80 | 1.9% |
| true divide different types | 60 | 1.4% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |        14100 | 0.0% |
|          hit |    128478360 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 700 | 48.6% |
| Failure | 740 | 51.4% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| class no vectorcall | 300 | 40.5% |
| cfunc noargs | 300 | 40.5% |
| cfunc varargs keywords | 80 | 10.8% |
| wrong number arguments | 60 | 8.1% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      6606120 | 3.4% |
|          hit |    188622540 | 96.6% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 60 | 3.5% |
| Failure | 1,640 | 96.5% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| float long | 1,640 | 100.0% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |         6060 | 0.7% |
|          hit |       865920 | 99.3% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 0 | 0.0% |
| Failure | 40 | 100.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| zip | 40 | 100.0% |


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
| specialization.deferred |          100 | 0.0% |
|          hit |    328881920 | 100.0% |
|         miss |        12240 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 840 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |          100 | 0.0% |
|          hit |    141592340 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,240 | 100.0% |
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

### POP_JUMP_IF_NONE

<details>
<summary> specialization stats for POP_JUMP_IF_NONE family </summary>

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
|          hit |     25447740 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 540 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |     35180400 | 100.0% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 2,282,803,500 | 51.4% |
| Not specialized | 581,217,980 | 13.1% |
| Specialized | 1,576,033,360 | 35.5% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| BINARY_SUBSCR | 175,566,540 | 54.1% |
| STORE_SUBSCR | 132,628,320 | 40.9% |
| BINARY_OP | 9,636,300 | 3.0% |
| COMPARE_OP | 6,606,120 | 2.0% |
| CALL | 14,100 | 0.0% |
| FOR_ITER | 6,060 | 0.0% |
| LOAD_GLOBAL | 100 | 0.0% |
| LOAD_ATTR | 100 | 0.0% |
| YIELD_VALUE | 0 | 0.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 0 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 12,240 | 100.0% |
| YIELD_VALUE | 0 | 0.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 0 | 0.0% |
| TO_BOOL_BOOL | 0 | 0.0% |
| SWAP | 0 | 0.0% |
| STORE_SUBSCR_LIST_INT | 0 | 0.0% |
| STORE_FAST_STORE_FAST | 0 | 0.0% |
| STORE_FAST_LOAD_FAST | 0 | 0.0% |
| STORE_FAST | 0 | 0.0% |
| STORE_ATTR_INSTANCE_VALUE | 0 | 0.0% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 6,373,980 | 4.5% |
| Calls to Python functions inlined | 136,461,240 | 95.5% |
| Calls via PyEval_EvalFrame (total) | 6,373,980 | 4.5% |
| Calls via PyEval_EvalFrame (vector) | 6,373,980 | 4.5% |
| Calls via PyEval_EvalFrame (generator) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 6,373,980 | 4.5% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 6,373,800 | 4.5% |
| Calls via PyEval_EvalFrame (function ex) | 600 | 0.0% |
| Calls via PyEval_EvalFrame (api) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frames pushed | 142,235,340 | 99.6% |
| Frame objects created | 0 | 0.0% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 614,043,200 | 57.5% |
| Frees to freelist | 614,043,240 |  |
| Allocations | 454,712,960 | 42.5% |
| Allocations to 512 bytes | 454,700,440 | 42.5% |
| Allocations to 4 kbytes | 12,100 | 0.0% |
| Allocations over 4 kbytes | 420 | 0.0% |
| Frees | 454,712,820 |  |
| New values | 180 |  |
| Interpreter increfs | 1,614,123,200 | 49.2% |
| Interpreter decrefs | 2,058,018,780 | 47.3% |
| Increfs | 1,663,946,586 | 50.8% |
| Decrefs | 2,288,774,366 | 52.7% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 0 | 0.0% |
| Method cache hits | 13,391 |  |
| Method cache misses | 29 |  |
| Method cache collisions | 32 |  |
| Method cache dunder hits | 66,156,397 |  |
| Method cache dunder misses | 3 |  |


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

## Meta stats

<details>
<summary> Meta statistics </summary>

| | Count | 
|---|---:|
| Number of data files | 100 |


</details>

---
Stats gathered on: 2023-09-27
