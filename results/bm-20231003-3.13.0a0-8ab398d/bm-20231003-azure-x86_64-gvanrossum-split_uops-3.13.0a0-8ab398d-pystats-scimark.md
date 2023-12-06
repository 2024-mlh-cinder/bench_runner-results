
# Pystats results

- benchmark: scimark
- fork: gvanrossum
- ref: split-uops
- commit hash: 8ab398d
- commit date: 2023-10-03T16:05:03-07:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 1,254,390,780 | 17.5% | 17.5% |  |
| LOAD_FAST_LOAD_FAST | 743,359,500 | 10.4% | 27.9% |  |
| STORE_FAST | 497,252,220 | 7.0% | 34.9% |  |
| BINARY_SUBSCR | 462,433,680 | 6.5% | 41.4% |  |
| LOAD_CONST | 415,543,380 | 5.8% | 47.2% |  |
| BINARY_OP_ADD_INT | 276,142,920 | 3.9% | 51.0% |  |
| POP_JUMP_IF_FALSE | 268,109,040 | 3.7% | 54.8% |  |
| LOAD_ATTR_INSTANCE_VALUE | 262,318,500 | 3.7% | 58.4% |  |
| SWAP | 244,319,040 | 3.4% | 61.9% |  |
| COPY | 244,312,800 | 3.4% | 65.3% |  |
| BINARY_OP_MULTIPLY_FLOAT | 239,032,140 | 3.3% | 68.6% |  |
| STORE_SUBSCR | 190,460,900 | 2.7% | 71.3% |  |
| COMPARE_OP_INT | 182,325,540 | 2.5% | 73.8% |  |
| BINARY_OP_ADD_FLOAT | 169,155,720 | 2.4% | 76.2% |  |
| RESUME_CHECK | 142,835,160 | 2.0% | 78.2% |  |
| BINARY_OP_SUBTRACT_FLOAT | 142,442,580 | 2.0% | 80.2% |  |
| FOR_ITER_RANGE | 141,877,200 | 2.0% | 82.2% |  |
| LOAD_GLOBAL_BUILTIN | 141,374,160 | 2.0% | 84.2% |  |
| JUMP_BACKWARD | 137,993,940 | 1.9% | 86.1% |  |
| RETURN_VALUE | 135,842,700 | 1.9% | 88.0% |  |
| BINARY_OP_MULTIPLY_INT | 105,275,640 | 1.5% | 89.5% |  |
| BINARY_SUBSCR_GETITEM | 88,538,340 | 1.2% | 90.7% |  |
| TO_BOOL_BOOL | 73,060,620 | 1.0% | 91.7% |  |
| JUMP_FORWARD | 70,645,560 | 1.0% | 92.7% |  |
| CALL_ISINSTANCE | 60,337,740 | 0.8% | 93.5% |  |
| BINARY_SUBSCR_LIST_INT | 60,326,340 | 0.8% | 94.4% |  |
| STORE_FAST_STORE_FAST | 47,903,340 | 0.7% | 95.1% |  |
| CALL_PY_EXACT_ARGS | 47,322,060 | 0.7% | 95.7% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 47,297,700 | 0.7% | 96.4% |  |
| BINARY_OP_SUBTRACT_INT | 41,629,200 | 0.6% | 97.0% |  |
| BUILD_TUPLE | 35,774,400 | 0.5% | 97.5% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 35,180,400 | 0.5% | 98.0% |  |
| BINARY_OP | 31,170,840 | 0.4% | 98.4% |  |
| STORE_ATTR_INSTANCE_VALUE | 25,447,740 | 0.4% | 98.7% |  |
| CALL_BUILTIN_CLASS | 20,395,200 | 0.3% | 99.0% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 19,097,160 | 0.3% | 99.3% | 0.1% |
| COMPARE_OP | 12,732,100 | 0.2% | 99.5% |  |
| GET_ITER | 7,609,380 | 0.1% | 99.6% |  |
| RETURN_CONST | 6,392,640 | 0.1% | 99.7% |  |
| INTERPRETER_EXIT | 6,373,980 | 0.1% | 99.8% |  |
| POP_JUMP_IF_TRUE | 6,303,000 | 0.1% | 99.9% |  |
| COMPARE_OP_FLOAT | 6,297,000 | 0.1% | 99.9% |  |
| BINARY_SUBSCR_TUPLE_INT | 1,200,000 | 0.0% | 100.0% |  |
| POP_TOP | 618,840 | 0.0% | 100.0% |  |
| FOR_ITER_GEN | 600,060 | 0.0% | 100.0% |  |
| YIELD_VALUE | 600,000 | 0.0% | 100.0% |  |
| CALL_BUILTIN_O | 423,180 | 0.0% | 100.0% |  |
| LOAD_GLOBAL_MODULE | 218,180 | 0.0% | 100.0% |  |
| LOAD_ATTR_MODULE | 180,800 | 0.0% | 100.0% |  |
| LIST_APPEND | 134,880 | 0.0% | 100.0% |  |
| STORE_FAST_LOAD_FAST | 122,880 | 0.0% | 100.0% |  |
| PUSH_NULL | 121,560 | 0.0% | 100.0% |  |
| EXTENDED_ARG | 60,000 | 0.0% | 100.0% |  |
| CALL | 15,540 | 0.0% | 100.0% |  |
| BUILD_LIST | 13,080 | 0.0% | 100.0% |  |
| STORE_SUBSCR_LIST_INT | 11,400 | 0.0% | 100.0% |  |
| FOR_ITER | 6,100 | 0.0% | 100.0% |  |
| STORE_SLICE | 6,060 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 1,340 | 0.0% | 100.0% |  |
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
| RETURN_GENERATOR | 60 | 0.0% | 100.0% |  |
| END_FOR | 60 | 0.0% | 100.0% |  |
| BINARY_SLICE | 60 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| STORE_FAST LOAD_FAST_LOAD_FAST | 249,880,740 | 3.5% | 3.5% |
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 208,647,320 | 2.9% | 6.4% |
| LOAD_FAST_LOAD_FAST BINARY_SUBSCR | 189,857,760 | 2.7% | 9.1% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 182,313,540 | 2.5% | 11.6% |
| POP_JUMP_IF_FALSE LOAD_FAST | 165,565,020 | 2.3% | 13.9% |
| LOAD_CONST BINARY_OP_ADD_INT | 152,486,500 | 2.1% | 16.1% |
| LOAD_FAST LOAD_FAST | 147,492,000 | 2.1% | 18.1% |
| LOAD_FAST_LOAD_FAST LOAD_CONST | 144,376,800 | 2.0% | 20.1% |
| LOAD_CONST LOAD_FAST | 142,736,160 | 2.0% | 22.1% |
| JUMP_BACKWARD FOR_ITER_RANGE | 134,267,940 | 1.9% | 24.0% |
| FOR_ITER_RANGE STORE_FAST | 134,145,060 | 1.9% | 25.9% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 133,083,960 | 1.9% | 27.8% |
| BINARY_SUBSCR LOAD_FAST | 129,321,000 | 1.8% | 29.6% |
| LOAD_FAST LOAD_CONST | 119,647,920 | 1.7% | 31.2% |
| LOAD_FAST BINARY_OP_MULTIPLY_FLOAT | 117,045,000 | 1.6% | 32.9% |
| STORE_FAST LOAD_FAST | 116,460,360 | 1.6% | 34.5% |
| LOAD_FAST BINARY_OP_ADD_INT | 111,320,400 | 1.6% | 36.1% |
| BINARY_SUBSCR LOAD_FAST_LOAD_FAST | 107,036,880 | 1.5% | 37.6% |
| STORE_SUBSCR LOAD_FAST_LOAD_FAST | 104,081,400 | 1.5% | 39.0% |
| BINARY_OP_MULTIPLY_FLOAT BINARY_OP_ADD_FLOAT | 90,422,400 | 1.3% | 40.3% |
| BINARY_SUBSCR_GETITEM RESUME_CHECK | 88,538,340 | 1.2% | 41.5% |
| SWAP SWAP | 87,582,000 | 1.2% | 42.7% |
| SWAP STORE_SUBSCR | 87,582,000 | 1.2% | 44.0% |
| COPY COPY | 87,582,000 | 1.2% | 45.2% |
| COPY BINARY_SUBSCR | 87,582,000 | 1.2% | 46.4% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 73,515,600 | 1.0% | 47.4% |
| BINARY_OP_SUBTRACT_FLOAT LOAD_FAST_LOAD_FAST | 73,280,400 | 1.0% | 48.5% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 73,060,620 | 1.0% | 49.5% |
| BINARY_OP_ADD_FLOAT STORE_FAST | 72,582,000 | 1.0% | 50.5% |
| SWAP COPY | 69,148,800 | 1.0% | 51.5% |
| POP_JUMP_IF_FALSE JUMP_FORWARD | 69,148,800 | 1.0% | 52.4% |
| LOAD_FAST SWAP | 69,148,800 | 1.0% | 53.4% |
| LOAD_ATTR_INSTANCE_VALUE COMPARE_OP_INT | 69,148,800 | 1.0% | 54.4% |
| COPY COMPARE_OP_INT | 69,148,800 | 1.0% | 55.3% |
| BINARY_OP_ADD_INT BINARY_SUBSCR | 68,352,000 | 1.0% | 56.3% |
| BINARY_SUBSCR BINARY_OP_MULTIPLY_FLOAT | 67,701,000 | 0.9% | 57.2% |
| BINARY_SUBSCR STORE_FAST | 67,452,000 | 0.9% | 58.2% |
| LOAD_FAST BINARY_OP_SUBTRACT_FLOAT | 67,202,600 | 0.9% | 59.1% |
| STORE_SUBSCR JUMP_BACKWARD | 67,187,460 | 0.9% | 60.1% |
| STORE_FAST LOAD_CONST | 62,607,300 | 0.9% | 60.9% |
| BINARY_OP_MULTIPLY_FLOAT BINARY_OP_SUBTRACT_FLOAT | 62,517,000 | 0.9% | 61.8% |
| BINARY_OP_MULTIPLY_INT STORE_FAST | 61,563,180 | 0.9% | 62.7% |
| LOAD_FAST BINARY_OP_ADD_FLOAT | 61,440,000 | 0.9% | 63.5% |
| BINARY_OP_ADD_FLOAT SWAP | 61,440,000 | 0.9% | 64.4% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 60,337,980 | 0.8% | 65.2% |
| LOAD_GLOBAL_BUILTIN CALL_ISINSTANCE | 60,337,740 | 0.8% | 66.1% |
| LOAD_FAST LOAD_GLOBAL_BUILTIN | 60,337,740 | 0.8% | 66.9% |
| CALL_ISINSTANCE TO_BOOL_BOOL | 60,337,740 | 0.8% | 67.8% |
| LOAD_FAST_LOAD_FAST BINARY_SUBSCR_GETITEM | 59,726,340 | 0.8% | 68.6% |
| LOAD_FAST BINARY_SUBSCR_LIST_INT | 59,726,340 | 0.8% | 69.4% |
| BINARY_SUBSCR_LIST_INT RETURN_VALUE | 59,726,340 | 0.8% | 70.3% |
| RETURN_VALUE LOAD_FAST | 59,714,940 | 0.8% | 71.1% |
| STORE_FAST JUMP_BACKWARD | 58,879,080 | 0.8% | 71.9% |
| BINARY_OP_ADD_INT BINARY_OP_MULTIPLY_INT | 55,302,000 | 0.8% | 72.7% |
| LOAD_FAST_LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 53,671,080 | 0.8% | 73.5% |
| BINARY_OP_SUBTRACT_FLOAT STORE_FAST | 49,460,880 | 0.7% | 74.1% |
| BINARY_OP_MULTIPLY_FLOAT LOAD_FAST | 49,224,000 | 0.7% | 74.8% |
| BINARY_SUBSCR BINARY_SUBSCR | 48,112,980 | 0.7% | 75.5% |
| LOAD_FAST_LOAD_FAST LOAD_FAST_LOAD_FAST | 48,000,120 | 0.7% | 76.2% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 47,322,000 | 0.7% | 76.8% |
| RESUME_CHECK LOAD_FAST | 47,312,640 | 0.7% | 77.5% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 47,174,640 | 0.7% | 78.2% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 45,723,780 | 0.6% | 78.8% |
| BINARY_OP_ADD_INT STORE_SUBSCR | 39,732,000 | 0.6% | 79.4% |
| LOAD_FAST BINARY_SUBSCR | 39,716,940 | 0.6% | 79.9% |
| LOAD_FAST_LOAD_FAST COPY | 36,864,000 | 0.5% | 80.4% |
| JUMP_FORWARD LOAD_FAST_LOAD_FAST | 36,071,160 | 0.5% | 80.9% |
| LOAD_CONST BINARY_OP_SUBTRACT_INT | 35,551,200 | 0.5% | 81.4% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST_STORE_FAST | 35,180,400 | 0.5% | 81.9% |
| LOAD_FAST_LOAD_FAST CALL_PY_EXACT_ARGS | 34,586,440 | 0.5% | 82.4% |
| RESUME_CHECK LOAD_CONST | 34,580,460 | 0.5% | 82.9% |
| LOAD_FAST UNPACK_SEQUENCE_TWO_TUPLE | 34,574,400 | 0.5% | 83.4% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST_LOAD_FAST | 34,574,400 | 0.5% | 83.9% |
| LOAD_ATTR_INSTANCE_VALUE BINARY_OP_MULTIPLY_INT | 34,574,400 | 0.5% | 84.3% |
| JUMP_FORWARD LOAD_CONST | 34,574,400 | 0.5% | 84.8% |
| BINARY_OP_MULTIPLY_INT LOAD_FAST | 34,574,400 | 0.5% | 85.3% |
| BINARY_OP_ADD_INT RETURN_VALUE | 34,574,400 | 0.5% | 85.8% |
| LOAD_FAST_LOAD_FAST STORE_SUBSCR | 33,707,400 | 0.5% | 86.3% |
| BINARY_OP STORE_FAST | 31,004,340 | 0.4% | 86.7% |
| BINARY_OP_ADD_INT COPY | 30,720,000 | 0.4% | 87.1% |
| BINARY_OP_ADD_INT LOAD_FAST | 30,659,280 | 0.4% | 87.6% |
| BINARY_OP_SUBTRACT_INT STORE_FAST | 30,033,000 | 0.4% | 88.0% |
| STORE_FAST_STORE_FAST LOAD_FAST | 29,412,000 | 0.4% | 88.4% |
| RETURN_VALUE BINARY_SUBSCR | 28,812,000 | 0.4% | 88.8% |
| BUILD_TUPLE BINARY_SUBSCR_GETITEM | 28,812,000 | 0.4% | 89.2% |
| BINARY_SUBSCR RETURN_VALUE | 28,812,000 | 0.4% | 89.6% |
| POP_JUMP_IF_FALSE LOAD_FAST_LOAD_FAST | 28,688,340 | 0.4% | 90.0% |
| LOAD_CONST COMPARE_OP_INT | 25,517,880 | 0.4% | 90.4% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 25,446,200 | 0.4% | 90.7% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST | 25,445,940 | 0.4% | 91.1% |
| LOAD_CONST BINARY_OP | 24,570,460 | 0.3% | 91.4% |
| LOAD_FAST_LOAD_FAST BINARY_OP_MULTIPLY_FLOAT | 24,156,000 | 0.3% | 91.7% |
| LOAD_FAST BUILD_TUPLE | 23,649,600 | 0.3% | 92.1% |
| BINARY_OP_ADD_FLOAT LOAD_FAST_LOAD_FAST | 23,368,260 | 0.3% | 92.4% |
| LOAD_FAST COPY | 19,998,000 | 0.3% | 92.7% |
| BINARY_OP_SUBTRACT_FLOAT SWAP | 19,701,000 | 0.3% | 93.0% |
| LOAD_FAST_LOAD_FAST COMPARE_OP_INT | 18,492,000 | 0.3% | 93.2% |
| RETURN_VALUE BINARY_OP_ADD_FLOAT | 17,287,200 | 0.2% | 93.5% |
| LOAD_FAST STORE_SUBSCR | 16,667,940 | 0.2% | 93.7% |
| LOAD_FAST CALL_BUILTIN_CLASS | 13,231,320 | 0.2% | 93.9% |


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
| LOAD_FAST_LOAD_FAST | 189,857,760 | 41.1% |
| COPY | 87,582,000 | 18.9% |
| BINARY_OP_ADD_INT | 68,352,000 | 14.8% |
| BINARY_SUBSCR | 48,112,980 | 10.4% |
| LOAD_FAST | 39,716,940 | 8.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 129,321,000 | 28.0% |
| LOAD_FAST_LOAD_FAST | 107,036,880 | 23.1% |
| BINARY_OP_MULTIPLY_FLOAT | 67,701,000 | 14.6% |
| STORE_FAST | 67,452,000 | 14.6% |
| BINARY_SUBSCR | 48,112,980 | 10.4% |


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
| CALL_BUILTIN_CLASS | 7,608,960 | 100.0% |
| LOAD_FAST | 300 | 0.0% |
| RETURN_GENERATOR | 60 | 0.0% |
| CALL | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_RANGE | 7,609,080 | 100.0% |
| LOAD_FAST_AND_CLEAR | 180 | 0.0% |
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
| JUMP_BACKWARD | 603,180 | 97.5% |
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
| SWAP | 87,582,000 | 46.0% |
| BINARY_OP_ADD_INT | 39,732,000 | 20.9% |
| LOAD_FAST_LOAD_FAST | 33,707,400 | 17.7% |
| LOAD_FAST | 16,667,940 | 8.8% |
| BUILD_TUPLE | 6,362,400 | 3.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 104,081,400 | 54.6% |
| JUMP_BACKWARD | 67,187,460 | 35.3% |
| LOAD_FAST | 12,782,880 | 6.7% |
| RETURN_CONST | 6,362,400 | 3.3% |
| STORE_SUBSCR | 46,700 | 0.0% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 24,570,460 | 78.8% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 6,367,980 | 20.4% |
| LOAD_FAST | 81,540 | 0.3% |
| LOAD_FAST_LOAD_FAST | 66,220 | 0.2% |
| BINARY_OP_MULTIPLY_FLOAT | 60,000 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 31,004,340 | 99.5% |
| LOAD_GLOBAL_MODULE | 60,000 | 0.2% |
| CALL_BUILTIN_O | 60,000 | 0.2% |
| BINARY_OP | 15,580 | 0.0% |
| LIST_APPEND | 12,000 | 0.0% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 12,600 | 96.3% |
| LOAD_FAST | 300 | 2.3% |
| SWAP | 180 | 1.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 12,600 | 96.3% |
| LOAD_DEREF | 300 | 2.3% |
| SWAP | 180 | 1.4% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_LIST | 12,600 | 81.1% |
| PUSH_NULL | 900 | 5.8% |
| CALL | 760 | 4.9% |
| LOAD_FAST | 500 | 3.2% |
| LOAD_FAST_LOAD_FAST | 260 | 1.7% |

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
| LOAD_CONST | 12,728,940 | 100.0% |
| COMPARE_OP | 3,160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 12,728,880 | 100.0% |
| COMPARE_OP | 3,160 | 0.0% |
| COMPARE_OP_INT | 60 | 0.0% |


</details>

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY | 87,582,000 | 35.8% |
| SWAP | 69,148,800 | 28.3% |
| LOAD_FAST_LOAD_FAST | 36,864,000 | 15.1% |
| BINARY_OP_ADD_INT | 30,720,000 | 12.6% |
| LOAD_FAST | 19,998,000 | 8.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 87,582,000 | 35.8% |
| BINARY_SUBSCR | 87,582,000 | 35.8% |
| COMPARE_OP_INT | 69,148,800 | 28.3% |


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

### EXTENDED_ARG

<details>
<summary> Successors and predecessors for EXTENDED_ARG </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 54,000 | 90.0% |
| COMPARE_OP_INT | 6,000 | 10.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 54,000 | 90.0% |
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
| STORE_SUBSCR | 67,187,460 | 48.7% |
| STORE_FAST | 58,879,080 | 42.7% |
| FOR_ITER_RANGE | 6,507,360 | 4.7% |
| POP_JUMP_IF_FALSE | 3,066,000 | 2.2% |
| POP_JUMP_IF_TRUE | 1,555,980 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_RANGE | 134,267,940 | 97.3% |
| LOAD_FAST_LOAD_FAST | 3,012,000 | 2.2% |
| FOR_ITER_GEN | 600,000 | 0.4% |
| LOAD_FAST | 54,000 | 0.0% |
| LOAD_CONST | 54,000 | 0.0% |


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
| JUMP_BACKWARD | 134,880 | 100.0% |


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
| LOAD_FAST_LOAD_FAST | 144,376,800 | 34.7% |
| LOAD_FAST | 119,647,920 | 28.8% |
| STORE_FAST | 62,607,300 | 15.1% |
| RESUME_CHECK | 34,580,460 | 8.3% |
| JUMP_FORWARD | 34,574,400 | 8.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 152,486,500 | 36.7% |
| LOAD_FAST | 142,736,160 | 34.3% |
| BINARY_OP_SUBTRACT_INT | 35,551,200 | 8.6% |
| COMPARE_OP_INT | 25,517,880 | 6.1% |
| BINARY_OP | 24,570,460 | 5.9% |


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
| POP_JUMP_IF_FALSE | 165,565,020 | 13.2% |
| LOAD_FAST | 147,492,000 | 11.8% |
| LOAD_CONST | 142,736,160 | 11.4% |
| LOAD_ATTR_INSTANCE_VALUE | 133,083,960 | 10.6% |
| BINARY_SUBSCR | 129,321,000 | 10.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 208,647,320 | 16.6% |
| LOAD_FAST | 147,492,000 | 11.8% |
| LOAD_CONST | 119,647,920 | 9.5% |
| BINARY_OP_MULTIPLY_FLOAT | 117,045,000 | 9.3% |
| BINARY_OP_ADD_INT | 111,320,400 | 8.9% |


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
| STORE_FAST | 249,880,740 | 33.6% |
| BINARY_SUBSCR | 107,036,880 | 14.4% |
| STORE_SUBSCR | 104,081,400 | 14.0% |
| BINARY_OP_SUBTRACT_FLOAT | 73,280,400 | 9.9% |
| LOAD_FAST_LOAD_FAST | 48,000,120 | 6.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR | 189,857,760 | 25.5% |
| LOAD_CONST | 144,376,800 | 19.4% |
| BINARY_SUBSCR_GETITEM | 59,726,340 | 8.0% |
| LOAD_ATTR_INSTANCE_VALUE | 53,671,080 | 7.2% |
| LOAD_FAST_LOAD_FAST | 48,000,120 | 6.5% |


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
| FOR_ITER_RANGE | 140 | 10.4% |

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
| COMPARE_OP_INT | 182,313,540 | 68.0% |
| TO_BOOL_BOOL | 73,060,620 | 27.3% |
| COMPARE_OP | 12,728,880 | 4.7% |
| EXTENDED_ARG | 6,000 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 165,565,020 | 61.8% |
| JUMP_FORWARD | 69,148,800 | 25.8% |
| LOAD_FAST_LOAD_FAST | 28,688,340 | 10.7% |
| JUMP_BACKWARD | 3,066,000 | 1.1% |
| LOAD_CONST | 1,511,880 | 0.6% |


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
| JUMP_BACKWARD | 1,555,980 | 24.7% |
| LOAD_GLOBAL_BUILTIN | 5,940 | 0.1% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_SUBSCR | 6,362,400 | 99.5% |
| STORE_SUBSCR_LIST_INT | 11,400 | 0.2% |
| FOR_ITER_RANGE | 9,180 | 0.1% |
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
| FOR_ITER_RANGE | 134,145,060 | 27.0% |
| BINARY_OP_ADD_FLOAT | 72,582,000 | 14.6% |
| BINARY_SUBSCR | 67,452,000 | 13.6% |
| BINARY_OP_MULTIPLY_INT | 61,563,180 | 12.4% |
| BINARY_OP_SUBTRACT_FLOAT | 49,460,880 | 9.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 249,880,740 | 50.3% |
| LOAD_FAST | 116,460,360 | 23.4% |
| LOAD_CONST | 62,607,300 | 12.6% |
| JUMP_BACKWARD | 58,879,080 | 11.8% |
| LOAD_GLOBAL_BUILTIN | 7,788,620 | 1.6% |


</details>

### STORE_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_RANGE | 122,880 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 122,880 | 100.0% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 35,180,400 | 73.4% |
| LOAD_ATTR_INSTANCE_VALUE | 12,722,940 | 26.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 29,412,000 | 61.4% |
| STORE_FAST | 12,722,880 | 26.6% |
| LOAD_FAST_LOAD_FAST | 5,768,400 | 12.0% |
| LOAD_GLOBAL_BUILTIN | 40 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 87,582,000 | 35.8% |
| LOAD_FAST | 69,148,800 | 28.3% |
| BINARY_OP_ADD_FLOAT | 61,440,000 | 25.1% |
| BINARY_OP_SUBTRACT_FLOAT | 19,701,000 | 8.1% |
| BINARY_OP_MULTIPLY_FLOAT | 6,441,000 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 87,582,000 | 35.8% |
| STORE_SUBSCR | 87,582,000 | 35.8% |
| COPY | 69,148,800 | 28.3% |
| LOAD_FAST_LOAD_FAST | 5,700 | 0.0% |
| STORE_FAST | 180 | 0.0% |


</details>

### BINARY_OP_ADD_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_MULTIPLY_FLOAT | 90,422,400 | 53.5% |
| LOAD_FAST | 61,440,000 | 36.3% |
| RETURN_VALUE | 17,287,200 | 10.2% |
| BINARY_OP | 6,120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 72,582,000 | 42.9% |
| SWAP | 61,440,000 | 36.3% |
| LOAD_FAST_LOAD_FAST | 23,368,260 | 13.8% |
| LOAD_CONST | 6,000,000 | 3.5% |
| BINARY_OP_MULTIPLY_FLOAT | 5,762,400 | 3.4% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 152,486,500 | 55.2% |
| LOAD_FAST | 111,320,400 | 40.3% |
| LOAD_FAST_LOAD_FAST | 12,336,000 | 4.5% |
| BINARY_OP | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR | 68,352,000 | 24.8% |
| BINARY_OP_MULTIPLY_INT | 55,302,000 | 20.0% |
| STORE_SUBSCR | 39,732,000 | 14.4% |
| RETURN_VALUE | 34,574,400 | 12.5% |
| COPY | 30,720,000 | 11.1% |


</details>

### BINARY_OP_MULTIPLY_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 117,045,000 | 49.0% |
| BINARY_SUBSCR | 67,701,000 | 28.3% |
| LOAD_FAST_LOAD_FAST | 24,156,000 | 10.1% |
| CALL_BUILTIN_CLASS | 12,782,880 | 5.3% |
| LOAD_CONST | 5,762,440 | 2.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_FLOAT | 90,422,400 | 37.8% |
| BINARY_OP_SUBTRACT_FLOAT | 62,517,000 | 26.2% |
| LOAD_FAST | 49,224,000 | 20.6% |
| RETURN_VALUE | 12,722,940 | 5.3% |
| LOAD_FAST_LOAD_FAST | 11,762,400 | 4.9% |


</details>

### BINARY_OP_MULTIPLY_INT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 55,302,000 | 52.5% |
| LOAD_ATTR_INSTANCE_VALUE | 34,574,400 | 32.8% |
| LOAD_FAST | 12,276,040 | 11.7% |
| LOAD_FAST_LOAD_FAST | 3,003,140 | 2.9% |
| LOAD_CONST | 120,000 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 61,563,180 | 58.5% |
| LOAD_FAST | 34,574,400 | 32.8% |
| CALL_BUILTIN_CLASS | 6,138,000 | 5.8% |
| LOAD_FAST_LOAD_FAST | 3,000,000 | 2.8% |
| BINARY_OP | 60 | 0.0% |


</details>

### BINARY_OP_SUBTRACT_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 67,202,600 | 47.2% |
| BINARY_OP_MULTIPLY_FLOAT | 62,517,000 | 43.9% |
| BINARY_SUBSCR | 12,722,880 | 8.9% |
| BINARY_OP | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 73,280,400 | 51.4% |
| STORE_FAST | 49,460,880 | 34.7% |
| SWAP | 19,701,000 | 13.8% |
| RETURN_VALUE | 300 | 0.0% |


</details>

### BINARY_OP_SUBTRACT_INT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 35,551,200 | 85.4% |
| LOAD_FAST_LOAD_FAST | 6,078,000 | 14.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 30,033,000 | 72.1% |
| LOAD_FAST | 5,762,400 | 13.8% |
| BUILD_TUPLE | 5,762,400 | 13.8% |
| CALL_BUILTIN_CLASS | 59,400 | 0.1% |
| COMPARE_OP_INT | 12,000 | 0.0% |


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
| LOAD_FAST | 13,231,320 | 64.9% |
| BINARY_OP_MULTIPLY_INT | 6,138,000 | 30.1% |
| BINARY_SUBSCR | 960,000 | 4.7% |
| BINARY_OP_SUBTRACT_INT | 59,400 | 0.3% |
| LOAD_ATTR_INSTANCE_VALUE | 6,040 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_MULTIPLY_FLOAT | 12,782,880 | 62.7% |
| GET_ITER | 7,608,960 | 37.3% |
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
| LOAD_FAST_LOAD_FAST | 34,586,440 | 73.1% |
| LOAD_ATTR_METHOD_WITH_VALUES | 12,722,920 | 26.9% |
| LOAD_FAST | 6,400 | 0.0% |
| LOAD_CONST | 6,000 | 0.0% |
| CALL | 300 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 47,322,000 | 100.0% |
| RETURN_GENERATOR | 60 | 0.0% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 69,148,800 | 37.9% |
| COPY | 69,148,800 | 37.9% |
| LOAD_CONST | 25,517,880 | 14.0% |
| LOAD_FAST_LOAD_FAST | 18,492,000 | 10.1% |
| BINARY_OP_SUBTRACT_INT | 12,000 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 182,313,540 | 100.0% |
| POP_JUMP_IF_TRUE | 6,000 | 0.0% |
| EXTENDED_ARG | 6,000 | 0.0% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 134,267,940 | 94.6% |
| GET_ITER | 7,609,080 | 5.4% |
| SWAP | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 134,145,060 | 94.6% |
| JUMP_BACKWARD | 6,507,360 | 4.6% |
| LOAD_FAST_LOAD_FAST | 971,940 | 0.7% |
| STORE_FAST_LOAD_FAST | 122,880 | 0.1% |
| LOAD_GLOBAL_BUILTIN | 60,040 | 0.0% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 208,647,320 | 79.5% |
| LOAD_FAST_LOAD_FAST | 53,671,080 | 20.5% |
| LOAD_ATTR | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 133,083,960 | 50.7% |
| COMPARE_OP_INT | 69,148,800 | 26.4% |
| BINARY_OP_MULTIPLY_INT | 34,574,400 | 13.2% |
| STORE_FAST_STORE_FAST | 12,722,940 | 4.9% |
| TO_BOOL_BOOL | 12,722,880 | 4.9% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 47,174,640 | 99.7% |
| STORE_FAST_LOAD_FAST | 122,880 | 0.3% |
| LOAD_ATTR | 140 | 0.0% |
| RETURN_VALUE | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 34,574,400 | 73.1% |
| CALL_PY_EXACT_ARGS | 12,722,920 | 26.9% |
| LOAD_FAST | 300 | 0.0% |
| LOAD_GLOBAL_MODULE | 40 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 180,500 | 99.8% |
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
| LOAD_FAST_LOAD_FAST | 6,370,680 | 33.4% |
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
| RESUME_CHECK | 60,337,980 | 42.7% |
| LOAD_FAST | 60,337,740 | 42.7% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 12,722,880 | 9.0% |
| STORE_FAST | 7,788,620 | 5.5% |
| LOAD_CONST | 63,040 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 73,515,600 | 52.0% |
| CALL_ISINSTANCE | 60,337,740 | 42.7% |
| LOAD_CONST | 6,257,580 | 4.4% |
| LOAD_FAST_LOAD_FAST | 1,263,240 | 0.9% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 138,760 | 63.6% |
| BINARY_OP | 60,000 | 27.5% |
| POP_JUMP_IF_FALSE | 12,000 | 5.5% |
| RESUME_CHECK | 3,200 | 1.5% |
| POP_TOP | 3,040 | 1.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 180,500 | 82.7% |
| LOAD_FAST_LOAD_FAST | 18,300 | 8.4% |
| LOAD_CONST | 12,960 | 5.9% |
| LOAD_FAST | 6,120 | 2.8% |
| LOAD_ATTR | 300 | 0.1% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_GETITEM | 88,538,340 | 62.0% |
| CALL_PY_EXACT_ARGS | 47,322,000 | 33.1% |
| CACHE | 6,373,980 | 4.5% |
| FOR_ITER_GEN | 600,000 | 0.4% |
| COPY_FREE_VARS | 300 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 60,337,980 | 42.2% |
| LOAD_FAST | 47,312,640 | 33.1% |
| LOAD_CONST | 34,580,460 | 24.2% |
| POP_TOP | 600,000 | 0.4% |
| LOAD_GLOBAL_MODULE | 3,200 | 0.0% |


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
| LOAD_FAST | 23,649,600 | 66.1% |
| BINARY_OP_SUBTRACT_INT | 5,762,400 | 16.1% |
| BINARY_OP_ADD_INT | 5,762,400 | 16.1% |
| LOAD_FAST_LOAD_FAST | 600,000 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_GETITEM | 28,812,000 | 80.5% |
| STORE_SUBSCR | 6,362,400 | 17.8% |
| YIELD_VALUE | 600,000 | 1.7% |


</details>

### YIELD_VALUE

<details>
<summary> Successors and predecessors for YIELD_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 600,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 600,000 | 100.0% |


</details>

### BINARY_SUBSCR_GETITEM

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_GETITEM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 59,726,340 | 67.5% |
| BUILD_TUPLE | 28,812,000 | 32.5% |

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
| specialization.deferred |    462320700 | 75.5% |
|          hit |    150064680 | 24.5% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 0 | 0.0% |
| Failure | 112,980 | 100.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| array int | 112,980 | 100.0% |


</details>

### STORE_SUBSCR

<details>
<summary> specialization stats for STORE_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |    190414200 | 100.0% |
|          hit |        11400 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 0 | 0.0% |
| Failure | 46,700 | 100.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| array int | 45,080 | 96.5% |
| py simple | 1,620 | 3.5% |


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
| specialization.deferred |     31161180 | 3.1% |
|          hit |    973678200 | 96.9% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 200 | 2.1% |
| Failure | 9,460 | 97.9% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| lshift | 3,040 | 32.1% |
| rshift | 2,980 | 31.5% |
| add different types | 1,660 | 17.5% |
| multiply different types | 640 | 6.8% |
| remainder | 420 | 4.4% |
| true divide other | 400 | 4.2% |
| floor divide | 140 | 1.5% |
| true divide float | 120 | 1.3% |
| true divide different types | 60 | 0.6% |


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
| specialization.deferred |     12728880 | 6.3% |
|          hit |    188622540 | 93.7% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 60 | 1.9% |
| Failure | 3,160 | 98.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| float long | 3,160 | 100.0% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |         6060 | 0.0% |
|          hit |    142477260 | 100.0% |

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
| Basic | 3,711,394,140 | 51.9% |
| Not specialized | 1,109,246,500 | 15.5% |
| Specialized | 2,330,330,620 | 32.6% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| BINARY_SUBSCR | 462,320,700 | 66.4% |
| STORE_SUBSCR | 190,414,200 | 27.3% |
| BINARY_OP | 31,161,180 | 4.5% |
| COMPARE_OP | 12,728,880 | 1.8% |
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
| Allocations | 454,712,920 | 42.5% |
| Allocations to 512 bytes | 454,700,440 | 42.5% |
| Allocations to 4 kbytes | 12,060 | 0.0% |
| Allocations over 4 kbytes | 420 | 0.0% |
| Frees | 454,712,820 |  |
| New values | 180 |  |
| Interpreter increfs | 2,656,384,700 | 83.1% |
| Interpreter decrefs | 3,737,668,380 | 87.6% |
| Increfs | 541,948,523 | 16.9% |
| Decrefs | 529,388,203 | 12.4% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 0 | 0.0% |
| Method cache hits | 13,390 |  |
| Method cache misses | 30 |  |
| Method cache collisions | 30 |  |
| Method cache dunder hits | 66,226,440 |  |
| Method cache dunder misses | 0 |  |


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
Stats gathered on: 2023-10-04
