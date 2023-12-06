
# Pystats results

- benchmark: fannkuch
- fork: gvanrossum
- ref: faster-uops
- commit hash: a2c4f00
- commit date: 2023-11-19T11:22:02-08:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_CONST | 373,657,900 | 17.8% | 17.8% |  |
| LOAD_FAST | 269,364,320 | 12.9% | 30.7% |  |
| POP_JUMP_IF_FALSE | 241,961,500 | 11.6% | 42.3% |  |
| LOAD_FAST_LOAD_FAST | 196,380,740 | 9.4% | 51.7% |  |
| BINARY_SUBSCR_LIST_INT | 138,702,060 | 6.6% | 58.3% |  |
| COMPARE_OP_INT | 136,572,000 | 6.5% | 64.8% |  |
| STORE_FAST | 135,767,360 | 6.5% | 71.3% |  |
| ENTER_EXECUTOR | 73,939,100 | 3.5% | 74.8% |  |
| BINARY_OP_ADD_INT | 66,817,440 | 3.2% | 78.0% |  |
| PUSH_NULL | 56,180,440 | 2.7% | 80.7% |  |
| COPY | 56,180,040 | 2.7% | 83.4% |  |
| SWAP | 56,180,040 | 2.7% | 86.1% |  |
| CALL_BUILTIN_FAST | 56,180,000 | 2.7% | 88.7% |  |
| TO_BOOL_INT | 45,965,080 | 2.2% | 90.9% |  |
| BINARY_OP_SUBTRACT_INT | 28,091,140 | 1.3% | 92.3% |  |
| STORE_SUBSCR_LIST_INT | 28,090,540 | 1.3% | 93.6% |  |
| POP_TOP | 28,090,180 | 1.3% | 95.0% |  |
| BINARY_SUBSCR | 22,988,760 | 1.1% | 96.1% |  |
| STORE_SLICE | 22,982,720 | 1.1% | 97.2% |  |
| BUILD_SLICE | 22,982,720 | 1.1% | 98.3% |  |
| BINARY_SLICE | 22,982,400 | 1.1% | 99.4% |  |
| JUMP_FORWARD | 13,574,720 | 0.6% | 100.0% |  |
| JUMP_BACKWARD | 1,360 | 0.0% | 100.0% |  |
| CALL | 720 | 0.0% | 100.0% |  |
| BINARY_OP | 360 | 0.0% | 100.0% |  |
| COMPARE_OP | 360 | 0.0% | 100.0% |  |
| CALL_BUILTIN_CLASS | 360 | 0.0% | 100.0% |  |
| LOAD_GLOBAL_BUILTIN | 360 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 320 | 0.0% | 100.0% |  |
| LOAD_ATTR | 280 | 0.0% | 100.0% |  |
| NOP | 160 | 0.0% | 100.0% |  |
| RETURN_VALUE | 160 | 0.0% | 100.0% |  |
| LOAD_DEREF | 160 | 0.0% | 100.0% |  |
| LOAD_ATTR_MODULE | 120 | 0.0% | 100.0% |  |
| LOAD_GLOBAL_MODULE | 120 | 0.0% | 100.0% |  |
| RESUME_CHECK | 120 | 0.0% | 100.0% |  |
| INTERPRETER_EXIT | 80 | 0.0% | 100.0% |  |
| STORE_SUBSCR | 80 | 0.0% | 100.0% |  |
| TO_BOOL | 80 | 0.0% | 100.0% |  |
| CALL_FUNCTION_EX | 80 | 0.0% | 100.0% |  |
| COPY_FREE_VARS | 80 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_FLOAT | 60 | 0.0% | 100.0% |  |
| RESUME | 40 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_FAST LOAD_CONST | 178,103,720 | 8.5% | 8.5% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 136,572,000 | 6.5% | 15.0% |
| STORE_FAST LOAD_FAST | 91,931,360 | 4.4% | 19.4% |
| POP_JUMP_IF_FALSE LOAD_FAST | 91,279,180 | 4.4% | 23.8% |
| POP_JUMP_IF_FALSE LOAD_FAST_LOAD_FAST | 91,256,840 | 4.4% | 28.1% |
| BINARY_SUBSCR_LIST_INT LOAD_CONST | 75,533,700 | 3.6% | 31.7% |
| LOAD_FAST_LOAD_FAST COMPARE_OP_INT | 71,923,980 | 3.4% | 35.2% |
| LOAD_CONST BINARY_OP_ADD_INT | 66,817,360 | 3.2% | 38.4% |
| LOAD_CONST BINARY_SUBSCR_LIST_INT | 65,318,720 | 3.1% | 41.5% |
| ENTER_EXECUTOR POP_JUMP_IF_FALSE | 59,424,200 | 2.8% | 44.3% |
| LOAD_CONST COMPARE_OP_INT | 47,444,580 | 2.3% | 46.6% |
| LOAD_CONST LOAD_CONST | 45,965,120 | 2.2% | 48.8% |
| BINARY_SUBSCR_LIST_INT STORE_FAST | 45,965,080 | 2.2% | 51.0% |
| TO_BOOL_INT POP_JUMP_IF_FALSE | 45,965,080 | 2.2% | 53.2% |
| LOAD_FAST TO_BOOL_INT | 45,965,040 | 2.2% | 55.4% |
| POP_JUMP_IF_FALSE ENTER_EXECUTOR | 45,849,740 | 2.2% | 57.6% |
| LOAD_FAST_LOAD_FAST BINARY_SUBSCR_LIST_INT | 45,293,240 | 2.2% | 59.7% |
| BINARY_OP_ADD_INT STORE_FAST | 43,834,680 | 2.1% | 61.8% |
| LOAD_CONST BINARY_OP_SUBTRACT_INT | 28,091,060 | 1.3% | 63.2% |
| LOAD_FAST PUSH_NULL | 28,090,260 | 1.3% | 64.5% |
| POP_TOP LOAD_FAST_LOAD_FAST | 28,090,020 | 1.3% | 65.9% |
| PUSH_NULL LOAD_CONST | 28,090,020 | 1.3% | 67.2% |
| PUSH_NULL LOAD_FAST_LOAD_FAST | 28,090,020 | 1.3% | 68.5% |
| COPY COPY | 28,090,020 | 1.3% | 69.9% |
| LOAD_FAST_LOAD_FAST PUSH_NULL | 28,090,020 | 1.3% | 71.2% |
| LOAD_FAST_LOAD_FAST COPY | 28,090,020 | 1.3% | 72.6% |
| SWAP SWAP | 28,090,020 | 1.3% | 73.9% |
| BINARY_OP_SUBTRACT_INT SWAP | 28,090,000 | 1.3% | 75.2% |
| CALL_BUILTIN_FAST POP_TOP | 28,090,000 | 1.3% | 76.6% |
| STORE_SUBSCR_LIST_INT LOAD_FAST_LOAD_FAST | 28,090,000 | 1.3% | 77.9% |
| COPY BINARY_SUBSCR_LIST_INT | 28,089,980 | 1.3% | 79.3% |
| LOAD_CONST CALL_BUILTIN_FAST | 28,089,980 | 1.3% | 80.6% |
| SWAP STORE_SUBSCR_LIST_INT | 28,089,980 | 1.3% | 82.0% |
| CALL_BUILTIN_FAST CALL_BUILTIN_FAST | 28,089,980 | 1.3% | 83.3% |
| LOAD_CONST LOAD_FAST | 22,982,800 | 1.1% | 84.4% |
| BINARY_SUBSCR LOAD_FAST | 22,982,740 | 1.1% | 85.5% |
| STORE_SLICE LOAD_FAST | 22,982,720 | 1.1% | 86.6% |
| BUILD_SLICE BINARY_SUBSCR | 22,982,720 | 1.1% | 87.7% |
| LOAD_CONST BUILD_SLICE | 22,982,720 | 1.1% | 88.8% |
| LOAD_FAST_LOAD_FAST LOAD_CONST | 22,982,720 | 1.1% | 89.9% |
| BINARY_OP_ADD_INT STORE_SLICE | 22,982,700 | 1.1% | 91.0% |
| LOAD_CONST STORE_FAST | 22,982,480 | 1.1% | 92.1% |
| STORE_FAST LOAD_CONST | 22,982,480 | 1.1% | 93.2% |
| BINARY_SLICE STORE_FAST | 22,982,400 | 1.1% | 94.3% |
| LOAD_CONST BINARY_SLICE | 22,982,400 | 1.1% | 95.4% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 20,853,200 | 1.0% | 96.4% |
| BINARY_SUBSCR_LIST_INT LOAD_FAST | 17,203,280 | 0.8% | 97.2% |
| LOAD_FAST COMPARE_OP_INT | 17,203,260 | 0.8% | 98.0% |
| ENTER_EXECUTOR ENTER_EXECUTOR | 14,514,900 | 0.7% | 98.7% |
| POP_JUMP_IF_FALSE JUMP_FORWARD | 13,574,720 | 0.6% | 99.4% |
| JUMP_FORWARD ENTER_EXECUTOR | 13,574,380 | 0.6% | 100.0% |
| BINARY_SUBSCR BINARY_SUBSCR | 5,800 | 0.0% | 100.0% |
| LOAD_FAST STORE_FAST | 1,280 | 0.0% | 100.0% |
| POP_JUMP_IF_FALSE JUMP_BACKWARD | 1,020 | 0.0% | 100.0% |
| JUMP_BACKWARD LOAD_FAST | 640 | 0.0% | 100.0% |
| JUMP_BACKWARD LOAD_FAST_LOAD_FAST | 640 | 0.0% | 100.0% |
| BINARY_OP_SUBTRACT_INT STORE_FAST | 600 | 0.0% | 100.0% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 560 | 0.0% | 100.0% |
| STORE_SUBSCR_LIST_INT LOAD_FAST | 540 | 0.0% | 100.0% |
| BINARY_OP_SUBTRACT_INT STORE_SUBSCR_LIST_INT | 520 | 0.0% | 100.0% |
| JUMP_FORWARD JUMP_BACKWARD | 340 | 0.0% | 100.0% |
| PUSH_NULL CALL | 320 | 0.0% | 100.0% |
| LOAD_CONST BINARY_OP | 320 | 0.0% | 100.0% |
| LOAD_CONST COMPARE_OP | 200 | 0.0% | 100.0% |
| CALL POP_TOP | 180 | 0.0% | 100.0% |
| COMPARE_OP POP_JUMP_IF_FALSE | 180 | 0.0% | 100.0% |
| COMPARE_OP COMPARE_OP_INT | 180 | 0.0% | 100.0% |
| LOAD_ATTR STORE_FAST | 180 | 0.0% | 100.0% |
| CALL_BUILTIN_CLASS STORE_FAST | 180 | 0.0% | 100.0% |
| CALL CALL | 160 | 0.0% | 100.0% |
| LOAD_FAST RETURN_VALUE | 160 | 0.0% | 100.0% |
| LOAD_FAST LOAD_ATTR | 160 | 0.0% | 100.0% |
| CALL STORE_FAST | 140 | 0.0% | 100.0% |
| BINARY_SUBSCR BINARY_SUBSCR_LIST_INT | 120 | 0.0% | 100.0% |
| CALL CALL_BUILTIN_CLASS | 120 | 0.0% | 100.0% |
| LOAD_CONST BINARY_SUBSCR | 120 | 0.0% | 100.0% |
| LOAD_FAST_LOAD_FAST COMPARE_OP | 120 | 0.0% | 100.0% |
| LOAD_GLOBAL LOAD_GLOBAL_BUILTIN | 120 | 0.0% | 100.0% |
| CALL_BUILTIN_CLASS CALL_BUILTIN_CLASS | 120 | 0.0% | 100.0% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 120 | 0.0% | 100.0% |
| LOAD_GLOBAL_BUILTIN LOAD_GLOBAL_BUILTIN | 120 | 0.0% | 100.0% |
| BINARY_OP STORE_FAST | 100 | 0.0% | 100.0% |
| NOP LOAD_DEREF | 80 | 0.0% | 100.0% |
| NOP LOAD_FAST | 80 | 0.0% | 100.0% |
| POP_TOP NOP | 80 | 0.0% | 100.0% |
| POP_TOP LOAD_FAST | 80 | 0.0% | 100.0% |
| PUSH_NULL LOAD_FAST | 80 | 0.0% | 100.0% |
| RETURN_VALUE INTERPRETER_EXIT | 80 | 0.0% | 100.0% |
| BINARY_OP BINARY_OP_ADD_INT | 80 | 0.0% | 100.0% |
| BINARY_OP BINARY_OP_SUBTRACT_INT | 80 | 0.0% | 100.0% |
| CALL LOAD_FAST | 80 | 0.0% | 100.0% |
| CALL_FUNCTION_EX COPY_FREE_VARS | 80 | 0.0% | 100.0% |
| JUMP_BACKWARD ENTER_EXECUTOR | 80 | 0.0% | 100.0% |
| LOAD_DEREF PUSH_NULL | 80 | 0.0% | 100.0% |
| LOAD_DEREF STORE_FAST | 80 | 0.0% | 100.0% |
| LOAD_FAST TO_BOOL | 80 | 0.0% | 100.0% |
| LOAD_FAST CALL | 80 | 0.0% | 100.0% |
| LOAD_FAST CALL_FUNCTION_EX | 80 | 0.0% | 100.0% |
| LOAD_FAST CALL_BUILTIN_CLASS | 80 | 0.0% | 100.0% |
| LOAD_FAST_LOAD_FAST BINARY_SUBSCR | 80 | 0.0% | 100.0% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### BINARY_SLICE

<details>
<summary> Successors and predecessors for BINARY_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 22,982,400 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 22,982,400 | 100.0% |


</details>

### STORE_SLICE

<details>
<summary> Successors and predecessors for STORE_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 22,982,700 | 100.0% |
| BINARY_OP | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 22,982,720 | 100.0% |


</details>

### CACHE

<details>
<summary> Successors and predecessors for CACHE </summary>

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 60 | 75.0% |
| RESUME | 20 | 25.0% |


</details>

### BINARY_SUBSCR

<details>
<summary> Successors and predecessors for BINARY_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_SLICE | 22,982,720 | 100.0% |
| BINARY_SUBSCR | 5,800 | 0.0% |
| LOAD_CONST | 120 | 0.0% |
| LOAD_FAST_LOAD_FAST | 80 | 0.0% |
| COPY | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 22,982,740 | 100.0% |
| BINARY_SUBSCR | 5,800 | 0.0% |
| BINARY_SUBSCR_LIST_INT | 120 | 0.0% |
| LOAD_CONST | 60 | 0.0% |
| STORE_FAST | 40 | 0.0% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 80 | 100.0% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 80 | 50.0% |
| STORE_FAST | 80 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_DEREF | 80 | 50.0% |
| LOAD_FAST | 80 | 50.0% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_FAST | 28,090,000 | 100.0% |
| CALL | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 28,090,020 | 100.0% |
| NOP | 80 | 0.0% |
| LOAD_FAST | 80 | 0.0% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 28,090,260 | 50.0% |
| LOAD_FAST_LOAD_FAST | 28,090,020 | 50.0% |
| LOAD_DEREF | 80 | 0.0% |
| LOAD_ATTR_MODULE | 60 | 0.0% |
| LOAD_ATTR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 28,090,020 | 50.0% |
| LOAD_FAST_LOAD_FAST | 28,090,020 | 50.0% |
| CALL | 320 | 0.0% |
| LOAD_FAST | 80 | 0.0% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 160 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 80 | 50.0% |
| LOAD_GLOBAL | 40 | 25.0% |
| LOAD_GLOBAL_MODULE | 40 | 25.0% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 40 | 50.0% |
| BINARY_OP | 20 | 25.0% |
| BINARY_OP_SUBTRACT_INT | 20 | 25.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_SUBSCR_LIST_INT | 40 | 50.0% |
| LOAD_FAST | 20 | 25.0% |
| LOAD_FAST_LOAD_FAST | 20 | 25.0% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 80 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 40 | 50.0% |
| TO_BOOL_INT | 40 | 50.0% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 320 | 88.9% |
| LOAD_FAST | 40 | 11.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 100 | 27.8% |
| BINARY_OP_ADD_INT | 80 | 22.2% |
| BINARY_OP_SUBTRACT_INT | 80 | 22.2% |
| STORE_SLICE | 20 | 5.6% |
| STORE_SUBSCR | 20 | 5.6% |


</details>

### BUILD_SLICE

<details>
<summary> Successors and predecessors for BUILD_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 22,982,720 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR | 22,982,720 | 100.0% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 320 | 44.4% |
| CALL | 160 | 22.2% |
| LOAD_FAST | 80 | 11.1% |
| CALL_BUILTIN_CLASS | 60 | 8.3% |
| LOAD_CONST | 40 | 5.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 180 | 25.0% |
| CALL | 160 | 22.2% |
| STORE_FAST | 140 | 19.4% |
| CALL_BUILTIN_CLASS | 120 | 16.7% |
| LOAD_FAST | 80 | 11.1% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 80 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY_FREE_VARS | 80 | 100.0% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 200 | 55.6% |
| LOAD_FAST_LOAD_FAST | 120 | 33.3% |
| LOAD_FAST | 40 | 11.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 180 | 50.0% |
| COMPARE_OP_INT | 180 | 50.0% |


</details>

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY | 28,090,020 | 50.0% |
| LOAD_FAST_LOAD_FAST | 28,090,020 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 28,090,020 | 50.0% |
| BINARY_SUBSCR_LIST_INT | 28,089,980 | 50.0% |
| BINARY_SUBSCR | 40 | 0.0% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 80 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 60 | 75.0% |
| RESUME | 20 | 25.0% |


</details>

### ENTER_EXECUTOR

<details>
<summary> Successors and predecessors for ENTER_EXECUTOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 45,849,740 | 62.0% |
| ENTER_EXECUTOR | 14,514,900 | 19.6% |
| JUMP_FORWARD | 13,574,380 | 18.4% |
| JUMP_BACKWARD | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 59,424,200 | 80.4% |
| ENTER_EXECUTOR | 14,514,900 | 19.6% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,020 | 75.0% |
| JUMP_FORWARD | 340 | 25.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 640 | 47.1% |
| LOAD_FAST_LOAD_FAST | 640 | 47.1% |
| ENTER_EXECUTOR | 80 | 5.9% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 13,574,720 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 13,574,380 | 100.0% |
| JUMP_BACKWARD | 340 | 0.0% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 160 | 57.1% |
| LOAD_ATTR | 40 | 14.3% |
| LOAD_GLOBAL | 40 | 14.3% |
| LOAD_GLOBAL_MODULE | 40 | 14.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 180 | 64.3% |
| LOAD_ATTR | 40 | 14.3% |
| LOAD_ATTR_MODULE | 40 | 14.3% |
| PUSH_NULL | 20 | 7.1% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 178,103,720 | 47.7% |
| BINARY_SUBSCR_LIST_INT | 75,533,700 | 20.2% |
| LOAD_CONST | 45,965,120 | 12.3% |
| PUSH_NULL | 28,090,020 | 7.5% |
| LOAD_FAST_LOAD_FAST | 22,982,720 | 6.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 66,817,360 | 17.9% |
| BINARY_SUBSCR_LIST_INT | 65,318,720 | 17.5% |
| COMPARE_OP_INT | 47,444,580 | 12.7% |
| LOAD_CONST | 45,965,120 | 12.3% |
| BINARY_OP_SUBTRACT_INT | 28,091,060 | 7.5% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| NOP | 80 | 50.0% |
| STORE_FAST | 80 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 80 | 50.0% |
| STORE_FAST | 80 | 50.0% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 91,931,360 | 34.1% |
| POP_JUMP_IF_FALSE | 91,279,180 | 33.9% |
| LOAD_CONST | 22,982,800 | 8.5% |
| BINARY_SUBSCR | 22,982,740 | 8.5% |
| STORE_SLICE | 22,982,720 | 8.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 178,103,720 | 66.1% |
| TO_BOOL_INT | 45,965,040 | 17.1% |
| PUSH_NULL | 28,090,260 | 10.4% |
| COMPARE_OP_INT | 17,203,260 | 6.4% |
| STORE_FAST | 1,280 | 0.0% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 91,256,840 | 46.5% |
| POP_TOP | 28,090,020 | 14.3% |
| PUSH_NULL | 28,090,020 | 14.3% |
| STORE_SUBSCR_LIST_INT | 28,090,000 | 14.3% |
| STORE_FAST | 20,853,200 | 10.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 71,923,980 | 36.6% |
| BINARY_SUBSCR_LIST_INT | 45,293,240 | 23.1% |
| PUSH_NULL | 28,090,020 | 14.3% |
| COPY | 28,090,020 | 14.3% |
| LOAD_CONST | 22,982,720 | 11.7% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 80 | 25.0% |
| LOAD_GLOBAL | 60 | 18.8% |
| LOAD_GLOBAL_BUILTIN | 60 | 18.8% |
| RETURN_VALUE | 40 | 12.5% |
| RESUME | 40 | 12.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 120 | 37.5% |
| LOAD_GLOBAL | 60 | 18.8% |
| LOAD_ATTR | 40 | 12.5% |
| LOAD_FAST | 40 | 12.5% |
| LOAD_GLOBAL_MODULE | 40 | 12.5% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 136,572,000 | 56.4% |
| ENTER_EXECUTOR | 59,424,200 | 24.6% |
| TO_BOOL_INT | 45,965,080 | 19.0% |
| COMPARE_OP | 180 | 0.0% |
| TO_BOOL | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 91,279,180 | 37.7% |
| LOAD_FAST_LOAD_FAST | 91,256,840 | 37.7% |
| ENTER_EXECUTOR | 45,849,740 | 18.9% |
| JUMP_FORWARD | 13,574,720 | 5.6% |
| JUMP_BACKWARD | 1,020 | 0.0% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_LIST_INT | 45,965,080 | 33.9% |
| BINARY_OP_ADD_INT | 43,834,680 | 32.3% |
| LOAD_CONST | 22,982,480 | 16.9% |
| BINARY_SLICE | 22,982,400 | 16.9% |
| LOAD_FAST | 1,280 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 91,931,360 | 67.7% |
| LOAD_CONST | 22,982,480 | 16.9% |
| LOAD_FAST_LOAD_FAST | 20,853,200 | 15.4% |
| NOP | 80 | 0.0% |
| LOAD_DEREF | 80 | 0.0% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 28,090,020 | 50.0% |
| BINARY_OP_SUBTRACT_INT | 28,090,000 | 50.0% |
| BINARY_OP | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 28,090,020 | 50.0% |
| STORE_SUBSCR_LIST_INT | 28,089,980 | 50.0% |
| STORE_SUBSCR | 40 | 0.0% |


</details>

### RESUME

<details>
<summary> Successors and predecessors for RESUME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 20 | 50.0% |
| COPY_FREE_VARS | 20 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL | 40 | 100.0% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 66,817,360 | 100.0% |
| BINARY_OP | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 43,834,680 | 65.6% |
| STORE_SLICE | 22,982,700 | 34.4% |
| CALL_BUILTIN_CLASS | 40 | 0.0% |
| CALL | 20 | 0.0% |


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
| LOAD_CONST | 28,091,060 | 100.0% |
| BINARY_OP | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 28,090,000 | 100.0% |
| STORE_FAST | 600 | 0.0% |
| STORE_SUBSCR_LIST_INT | 520 | 0.0% |
| STORE_SUBSCR | 20 | 0.0% |


</details>

### BINARY_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 65,318,720 | 47.1% |
| LOAD_FAST_LOAD_FAST | 45,293,240 | 32.7% |
| COPY | 28,089,980 | 20.3% |
| BINARY_SUBSCR | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 75,533,700 | 54.5% |
| STORE_FAST | 45,965,080 | 33.1% |
| LOAD_FAST | 17,203,280 | 12.4% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 120 | 33.3% |
| CALL_BUILTIN_CLASS | 120 | 33.3% |
| LOAD_FAST | 80 | 22.2% |
| BINARY_OP_ADD_INT | 40 | 11.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 180 | 50.0% |
| CALL_BUILTIN_CLASS | 120 | 33.3% |
| CALL | 60 | 16.7% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 28,089,980 | 50.0% |
| CALL_BUILTIN_FAST | 28,089,980 | 50.0% |
| CALL | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 28,090,000 | 50.0% |
| CALL_BUILTIN_FAST | 28,089,980 | 50.0% |
| CALL | 20 | 0.0% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 71,923,980 | 52.7% |
| LOAD_CONST | 47,444,580 | 34.7% |
| LOAD_FAST | 17,203,260 | 12.6% |
| COMPARE_OP | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 136,572,000 | 100.0% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 80 | 66.7% |
| LOAD_ATTR | 40 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 60 | 50.0% |
| STORE_FAST | 60 | 50.0% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL | 120 | 33.3% |
| LOAD_GLOBAL_BUILTIN | 120 | 33.3% |
| STORE_FAST | 80 | 22.2% |
| RESUME_CHECK | 40 | 11.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 120 | 33.3% |
| LOAD_GLOBAL_BUILTIN | 120 | 33.3% |
| LOAD_CONST | 60 | 16.7% |
| LOAD_GLOBAL | 60 | 16.7% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 40 | 33.3% |
| LOAD_GLOBAL | 40 | 33.3% |
| RESUME_CHECK | 40 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 80 | 66.7% |
| LOAD_ATTR | 40 | 33.3% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 60 | 50.0% |
| COPY_FREE_VARS | 60 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL | 40 | 33.3% |
| LOAD_GLOBAL_BUILTIN | 40 | 33.3% |
| LOAD_GLOBAL_MODULE | 40 | 33.3% |


</details>

### STORE_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 28,089,980 | 100.0% |
| BINARY_OP_SUBTRACT_INT | 520 | 0.0% |
| STORE_SUBSCR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 28,090,000 | 100.0% |
| LOAD_FAST | 540 | 0.0% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 45,965,040 | 100.0% |
| TO_BOOL | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 45,965,080 | 100.0% |


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
|     deferred | 180 | 0.0% |
|          hit | 94,908,640 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 180 | 100.0% |
| Failure | 0 | 0.0% |


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
|     deferred | 22,982,840 | 14.2% |
|          hit | 138,702,060 | 85.8% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 120 | 2.0% |
| Failure | 5,800 | 98.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| list slice | 5,800 | 100.0% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 480 | 0.0% |
|          hit | 56,180,360 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 160 | 66.7% |
| Failure | 80 | 33.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| cfunc noargs | 60 | 75.0% |
| other | 20 | 25.0% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 180 | 0.0% |
|          hit | 136,572,000 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 180 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### LOAD_ATTR

<details>
<summary> specialization stats for LOAD_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 200 | 50.0% |
|          hit | 120 | 30.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 40 | 50.0% |
| Failure | 40 | 50.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| method | 40 | 100.0% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 160 | 20.0% |
|          hit | 480 | 60.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 160 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> specialization stats for POP_JUMP_IF_FALSE family </summary>


</details>

### STORE_SLICE

<details>
<summary> specialization stats for STORE_SLICE family </summary>


</details>

### STORE_SUBSCR

<details>
<summary> specialization stats for STORE_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 40 | 0.0% |
|          hit | 28,090,540 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 40 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 40 | 0.0% |
|          hit | 45,965,080 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 40 | 100.0% |
| Failure | 0 | 0.0% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 1,282,299,680 | 61.2% |
| Not specialized | 310,917,580 | 14.9% |
| Specialized hits | 500,419,400 | 23.9% |
| Specialized misses | 0 | 0.0% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| BINARY_SUBSCR | 22,982,840 | 100.0% |
| CALL | 480 | 0.0% |
| LOAD_ATTR | 200 | 0.0% |
| BINARY_OP | 180 | 0.0% |
| COMPARE_OP | 180 | 0.0% |
| LOAD_GLOBAL | 160 | 0.0% |
| STORE_SUBSCR | 40 | 0.0% |
| TO_BOOL | 40 | 0.0% |
| BINARY_SLICE | 0 | 0.0% |
| STORE_SLICE | 0 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 80 | 50.0% |
| Calls to Python functions inlined | 80 | 50.0% |
| Calls via PyEval_EvalFrame (total) | 80 | 50.0% |
| Calls via PyEval_EvalFrame (vector) | 80 | 50.0% |
| Calls via PyEval_EvalFrame (generator) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 80 | 50.0% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function ex) | 80 | 50.0% |
| Calls via PyEval_EvalFrame (api) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frame objects created | 0 | 0.0% |
| Frames pushed | 0 | 0.0% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 161,482,160 | 47.8% |
| Frees to freelist | 161,482,340 |  |
| Allocations | 175,998,420 | 52.2% |
| Allocations to 512 bytes | 175,998,360 | 52.2% |
| Allocations to 4 kbytes | 60 | 0.0% |
| Allocations over 4 kbytes | 0 | 0.0% |
| Frees | 175,998,081 |  |
| New values | 0 |  |
| Interpreter increfs | 860,502,980 | 86.1% |
| Interpreter decrefs | 1,321,967,360 | 90.5% |
| Increfs | 138,500,080 | 13.9% |
| Decrefs | 138,500,281 | 9.5% |
| Materialize dict (on request) | 0 |  |
| Materialize dict (new key) | 0 |  |
| Materialize dict (too big) | 0 |  |
| Materialize dict (str subclass) | 0 |  |
| Dematerialize dict | 0 |  |
| Method cache hits | 209 |  |
| Method cache misses | 31 |  |
| Method cache collisions | 31 |  |
| Method cache dunder hits | 0 |  |
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

## Optimization (Tier 2) stats

<details>
<summary> statistics about the Tier 2 optimizer </summary>

| | Count | Ratio | 
|---|---:|---:|
| Optimization attempts | 80 |  |
| Traces created | 80 | 100.0% |
| Trace stack overflow | 0 | 0.0% |
| Trace stack underflow | 0 | 0.0% |
| Trace too long | 0 | 0.0% |
| Trace too short | 0 | 0.0% |
| Inner loop found | 20 | 25.0% |
| Recursive call | 0 | 0.0% |
| Traces executed | 73,939,100 |  |
| Uops executed | 5,471,879,620 | 74.01 |

### Trace length histogram

<details>
<summary> trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 0 | 0.0% |
| <= 16 | 0 | 0.0% |
| <= 32 | 0 | 0.0% |
| <= 64 | 20 | 25.0% |
| <= 128 | 40 | 50.0% |
| <= 256 | 20 | 25.0% |


</details>

### Optimized trace length histogram

<details>
<summary> optimized trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 0 | 0.0% |
| <= 16 | 0 | 0.0% |
| <= 32 | 20 | 25.0% |
| <= 64 | 40 | 50.0% |
| <= 128 | 20 | 25.0% |


</details>

### Trace run length histogram

<details>
<summary> trace run length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 13,574,340 | 18.4% |
| <= 16 | 0 | 0.0% |
| <= 32 | 8,466,980 | 11.5% |
| <= 64 | 33,377,620 | 45.1% |
| <= 128 | 6,167,180 | 8.3% |
| <= 256 | 6,575,540 | 8.9% |
| <= 512 | 5,123,520 | 6.9% |
| <= 1,024 | 653,920 | 0.9% |


</details>

### Uop execution stats

<details>
<summary> uop execution stats </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 1,131,814,040 | 20.7% | 20.7% |  |
| LOAD_CONST | 869,415,860 | 15.9% | 36.6% |  |
| _SET_IP | 818,200,540 | 15.0% | 51.5% |  |
| _CHECK_VALIDITY | 523,671,600 | 9.6% | 61.1% |  |
| _GUARD_BOTH_INT | 294,528,940 | 5.4% | 66.5% |  |
| STORE_FAST | 251,885,200 | 4.6% | 71.1% |  |
| _BINARY_OP_ADD_INT | 231,033,760 | 4.2% | 75.3% |  |
| _GUARD_IS_TRUE_POP | 183,293,040 | 3.3% | 78.7% | 25.6% |
| BINARY_SUBSCR_LIST_INT | 177,379,660 | 3.2% | 81.9% |  |
| STORE_SLICE | 115,516,880 | 2.1% | 84.0% |  |
| BUILD_SLICE | 115,516,880 | 2.1% | 86.1% |  |
| TO_BOOL_INT | 115,516,880 | 2.1% | 88.2% |  |
| _BINARY_SUBSCR | 115,516,880 | 2.1% | 90.3% |  |
| _JUMP_TO_TOP | 97,795,860 | 1.8% | 92.1% |  |
| COMPARE_OP_INT | 90,892,620 | 1.7% | 93.8% |  |
| _BINARY_OP_SUBTRACT_INT | 63,495,180 | 1.2% | 94.9% |  |
| PUSH_NULL | 43,584,600 | 0.8% | 95.7% |  |
| COPY | 43,584,600 | 0.8% | 96.5% |  |
| SWAP | 43,584,600 | 0.8% | 97.3% |  |
| CALL_BUILTIN_FAST | 43,584,600 | 0.8% | 98.1% |  |
| STORE_SUBSCR_LIST_INT | 42,643,740 | 0.8% | 98.9% |  |
| _GUARD_IS_FALSE_POP | 23,116,460 | 0.4% | 99.3% | 54.1% |
| POP_TOP | 21,792,300 | 0.4% | 99.7% |  |
| _EXIT_TRACE | 14,514,900 | 0.3% | 100.0% |  |


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>


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
Stats gathered on: 2023-11-19
