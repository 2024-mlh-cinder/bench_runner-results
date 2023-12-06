
# Pystats results

- benchmark: fannkuch
- fork: mdboom
- ref: collect-tier2-stats
- commit hash: 8794817
- commit date: 2023-11-02T18:18:55-04:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 837,339,560 | 20.2% | 20.2% |  |
| LOAD_CONST | 824,638,160 | 19.9% | 40.0% |  |
| STORE_FAST | 366,801,120 | 8.8% | 48.9% |  |
| BINARY_OP_ADD_INT | 297,851,200 | 7.2% | 56.1% |  |
| POP_JUMP_IF_FALSE | 288,915,460 | 7.0% | 63.0% |  |
| BINARY_SUBSCR_LIST_INT | 244,139,520 | 5.9% | 68.9% |  |
| LOAD_FAST_LOAD_FAST | 190,199,040 | 4.6% | 73.5% |  |
| ENTER_EXECUTOR | 171,734,960 | 4.1% | 77.6% |  |
| TO_BOOL_INT | 161,481,960 | 3.9% | 81.5% |  |
| BINARY_SUBSCR | 138,533,860 | 3.3% | 84.8% |  |
| STORE_SLICE | 138,499,600 | 3.3% | 88.2% |  |
| COMPARE_OP_INT | 126,492,580 | 3.0% | 91.2% |  |
| PUSH_NULL | 55,239,920 | 1.3% | 92.6% |  |
| COPY | 55,239,520 | 1.3% | 93.9% |  |
| SWAP | 55,239,520 | 1.3% | 95.2% |  |
| CALL_BUILTIN_FAST | 55,239,480 | 1.3% | 96.6% |  |
| BINARY_OP_SUBTRACT_INT | 27,620,880 | 0.7% | 97.2% |  |
| STORE_SUBSCR_LIST_INT | 27,620,280 | 0.7% | 97.9% |  |
| POP_TOP | 27,619,920 | 0.7% | 98.6% |  |
| BUILD_SLICE | 22,982,720 | 0.6% | 99.1% |  |
| BINARY_SLICE | 22,982,400 | 0.6% | 99.7% |  |
| JUMP_FORWARD | 14,045,160 | 0.3% | 100.0% |  |
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
| LOAD_FAST LOAD_CONST | 635,333,000 | 15.3% | 15.3% |
| STORE_FAST LOAD_FAST | 322,965,120 | 7.8% | 23.1% |
| LOAD_CONST BINARY_OP_ADD_INT | 297,851,120 | 7.2% | 30.3% |
| LOAD_CONST BINARY_SUBSCR_LIST_INT | 175,997,360 | 4.2% | 34.5% |
| BINARY_SUBSCR_LIST_INT STORE_FAST | 161,481,960 | 3.9% | 38.4% |
| TO_BOOL_INT POP_JUMP_IF_FALSE | 161,481,960 | 3.9% | 42.3% |
| LOAD_FAST TO_BOOL_INT | 161,481,920 | 3.9% | 46.2% |
| BINARY_OP_ADD_INT STORE_FAST | 159,351,560 | 3.8% | 50.0% |
| LOAD_CONST LOAD_FAST | 138,499,680 | 3.3% | 53.4% |
| BINARY_SUBSCR LOAD_FAST | 138,499,620 | 3.3% | 56.7% |
| STORE_SLICE LOAD_FAST | 138,499,600 | 3.3% | 60.0% |
| BINARY_OP_ADD_INT STORE_SLICE | 138,499,580 | 3.3% | 63.4% |
| POP_JUMP_IF_FALSE ENTER_EXECUTOR | 136,368,500 | 3.3% | 66.7% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 126,492,580 | 3.0% | 69.7% |
| ENTER_EXECUTOR BINARY_SUBSCR | 115,516,880 | 2.8% | 72.5% |
| POP_JUMP_IF_FALSE LOAD_FAST_LOAD_FAST | 84,873,160 | 2.0% | 74.5% |
| LOAD_FAST_LOAD_FAST COMPARE_OP_INT | 71,453,720 | 1.7% | 76.2% |
| BINARY_SUBSCR_LIST_INT LOAD_CONST | 69,754,940 | 1.7% | 77.9% |
| POP_JUMP_IF_FALSE LOAD_FAST | 53,627,740 | 1.3% | 79.2% |
| LOAD_CONST LOAD_CONST | 45,965,120 | 1.1% | 80.3% |
| LOAD_CONST COMPARE_OP_INT | 42,136,080 | 1.0% | 81.3% |
| LOAD_FAST_LOAD_FAST BINARY_SUBSCR_LIST_INT | 40,522,320 | 1.0% | 82.3% |
| ENTER_EXECUTOR LOAD_FAST | 32,342,940 | 0.8% | 83.1% |
| LOAD_CONST BINARY_OP_SUBTRACT_INT | 27,620,800 | 0.7% | 83.8% |
| LOAD_FAST PUSH_NULL | 27,620,000 | 0.7% | 84.4% |
| POP_TOP LOAD_FAST_LOAD_FAST | 27,619,760 | 0.7% | 85.1% |
| PUSH_NULL LOAD_CONST | 27,619,760 | 0.7% | 85.8% |
| PUSH_NULL LOAD_FAST_LOAD_FAST | 27,619,760 | 0.7% | 86.4% |
| COPY COPY | 27,619,760 | 0.7% | 87.1% |
| LOAD_FAST_LOAD_FAST PUSH_NULL | 27,619,760 | 0.7% | 87.8% |
| LOAD_FAST_LOAD_FAST COPY | 27,619,760 | 0.7% | 88.4% |
| SWAP SWAP | 27,619,760 | 0.7% | 89.1% |
| BINARY_OP_SUBTRACT_INT SWAP | 27,619,740 | 0.7% | 89.8% |
| CALL_BUILTIN_FAST POP_TOP | 27,619,740 | 0.7% | 90.4% |
| STORE_SUBSCR_LIST_INT LOAD_FAST_LOAD_FAST | 27,619,740 | 0.7% | 91.1% |
| COPY BINARY_SUBSCR_LIST_INT | 27,619,720 | 0.7% | 91.8% |
| LOAD_CONST CALL_BUILTIN_FAST | 27,619,720 | 0.7% | 92.4% |
| SWAP STORE_SUBSCR_LIST_INT | 27,619,720 | 0.7% | 93.1% |
| CALL_BUILTIN_FAST CALL_BUILTIN_FAST | 27,619,720 | 0.7% | 93.7% |
| BUILD_SLICE BINARY_SUBSCR | 22,982,720 | 0.6% | 94.3% |
| LOAD_CONST BUILD_SLICE | 22,982,720 | 0.6% | 94.9% |
| LOAD_FAST_LOAD_FAST LOAD_CONST | 22,982,720 | 0.6% | 95.4% |
| LOAD_CONST STORE_FAST | 22,982,480 | 0.6% | 96.0% |
| STORE_FAST LOAD_CONST | 22,982,480 | 0.6% | 96.5% |
| BINARY_SLICE STORE_FAST | 22,982,400 | 0.6% | 97.1% |
| LOAD_CONST BINARY_SLICE | 22,982,400 | 0.6% | 97.6% |
| ENTER_EXECUTOR ENTER_EXECUTOR | 21,321,560 | 0.5% | 98.1% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 20,853,200 | 0.5% | 98.6% |
| POP_JUMP_IF_FALSE JUMP_FORWARD | 14,045,160 | 0.3% | 99.0% |
| JUMP_FORWARD ENTER_EXECUTOR | 14,044,820 | 0.3% | 99.3% |
| BINARY_SUBSCR_LIST_INT LOAD_FAST | 12,902,620 | 0.3% | 99.6% |
| LOAD_FAST COMPARE_OP_INT | 12,902,600 | 0.3% | 99.9% |
| ENTER_EXECUTOR LOAD_FAST_LOAD_FAST | 1,612,760 | 0.0% | 100.0% |
| ENTER_EXECUTOR POP_JUMP_IF_FALSE | 940,700 | 0.0% | 100.0% |
| BINARY_SUBSCR BINARY_SUBSCR | 34,020 | 0.0% | 100.0% |
| LOAD_FAST STORE_FAST | 1,280 | 0.0% | 100.0% |
| POP_JUMP_IF_FALSE JUMP_BACKWARD | 900 | 0.0% | 100.0% |
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
| ENTER_EXECUTOR JUMP_BACKWARD | 120 | 0.0% | 100.0% |
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
| BINARY_OP_ADD_INT | 138,499,580 | 100.0% |
| BINARY_OP | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 138,499,600 | 100.0% |


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
| ENTER_EXECUTOR | 115,516,880 | 83.4% |
| BUILD_SLICE | 22,982,720 | 16.6% |
| BINARY_SUBSCR | 34,020 | 0.0% |
| LOAD_CONST | 120 | 0.0% |
| LOAD_FAST_LOAD_FAST | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 138,499,620 | 100.0% |
| BINARY_SUBSCR | 34,020 | 0.0% |
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
| CALL_BUILTIN_FAST | 27,619,740 | 100.0% |
| CALL | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 27,619,760 | 100.0% |
| NOP | 80 | 0.0% |
| LOAD_FAST | 80 | 0.0% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 27,620,000 | 50.0% |
| LOAD_FAST_LOAD_FAST | 27,619,760 | 50.0% |
| LOAD_DEREF | 80 | 0.0% |
| LOAD_ATTR_MODULE | 60 | 0.0% |
| LOAD_ATTR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 27,619,760 | 50.0% |
| LOAD_FAST_LOAD_FAST | 27,619,760 | 50.0% |
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
| COPY | 27,619,760 | 50.0% |
| LOAD_FAST_LOAD_FAST | 27,619,760 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 27,619,760 | 50.0% |
| BINARY_SUBSCR_LIST_INT | 27,619,720 | 50.0% |
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
| POP_JUMP_IF_FALSE | 136,368,500 | 79.4% |
| ENTER_EXECUTOR | 21,321,560 | 12.4% |
| JUMP_FORWARD | 14,044,820 | 8.2% |
| JUMP_BACKWARD | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR | 115,516,880 | 67.3% |
| LOAD_FAST | 32,342,940 | 18.8% |
| ENTER_EXECUTOR | 21,321,560 | 12.4% |
| LOAD_FAST_LOAD_FAST | 1,612,760 | 0.9% |
| POP_JUMP_IF_FALSE | 940,700 | 0.5% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 900 | 66.2% |
| JUMP_FORWARD | 340 | 25.0% |
| ENTER_EXECUTOR | 120 | 8.8% |

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
| POP_JUMP_IF_FALSE | 14,045,160 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 14,044,820 | 100.0% |
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
| LOAD_FAST | 635,333,000 | 77.0% |
| BINARY_SUBSCR_LIST_INT | 69,754,940 | 8.5% |
| LOAD_CONST | 45,965,120 | 5.6% |
| PUSH_NULL | 27,619,760 | 3.3% |
| LOAD_FAST_LOAD_FAST | 22,982,720 | 2.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 297,851,120 | 36.1% |
| BINARY_SUBSCR_LIST_INT | 175,997,360 | 21.3% |
| LOAD_FAST | 138,499,680 | 16.8% |
| LOAD_CONST | 45,965,120 | 5.6% |
| COMPARE_OP_INT | 42,136,080 | 5.1% |


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
| STORE_FAST | 322,965,120 | 38.6% |
| LOAD_CONST | 138,499,680 | 16.5% |
| BINARY_SUBSCR | 138,499,620 | 16.5% |
| STORE_SLICE | 138,499,600 | 16.5% |
| POP_JUMP_IF_FALSE | 53,627,740 | 6.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 635,333,000 | 75.9% |
| TO_BOOL_INT | 161,481,920 | 19.3% |
| PUSH_NULL | 27,620,000 | 3.3% |
| COMPARE_OP_INT | 12,902,600 | 1.5% |
| STORE_FAST | 1,280 | 0.0% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 84,873,160 | 44.6% |
| POP_TOP | 27,619,760 | 14.5% |
| PUSH_NULL | 27,619,760 | 14.5% |
| STORE_SUBSCR_LIST_INT | 27,619,740 | 14.5% |
| STORE_FAST | 20,853,200 | 11.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 71,453,720 | 37.6% |
| BINARY_SUBSCR_LIST_INT | 40,522,320 | 21.3% |
| PUSH_NULL | 27,619,760 | 14.5% |
| COPY | 27,619,760 | 14.5% |
| LOAD_CONST | 22,982,720 | 12.1% |


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
| TO_BOOL_INT | 161,481,960 | 55.9% |
| COMPARE_OP_INT | 126,492,580 | 43.8% |
| ENTER_EXECUTOR | 940,700 | 0.3% |
| COMPARE_OP | 180 | 0.0% |
| TO_BOOL | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 136,368,500 | 47.2% |
| LOAD_FAST_LOAD_FAST | 84,873,160 | 29.4% |
| LOAD_FAST | 53,627,740 | 18.6% |
| JUMP_FORWARD | 14,045,160 | 4.9% |
| JUMP_BACKWARD | 900 | 0.0% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_LIST_INT | 161,481,960 | 44.0% |
| BINARY_OP_ADD_INT | 159,351,560 | 43.4% |
| LOAD_CONST | 22,982,480 | 6.3% |
| BINARY_SLICE | 22,982,400 | 6.3% |
| LOAD_FAST | 1,280 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 322,965,120 | 88.0% |
| LOAD_CONST | 22,982,480 | 6.3% |
| LOAD_FAST_LOAD_FAST | 20,853,200 | 5.7% |
| NOP | 80 | 0.0% |
| LOAD_DEREF | 80 | 0.0% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 27,619,760 | 50.0% |
| BINARY_OP_SUBTRACT_INT | 27,619,740 | 50.0% |
| BINARY_OP | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 27,619,760 | 50.0% |
| STORE_SUBSCR_LIST_INT | 27,619,720 | 50.0% |
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
| LOAD_CONST | 297,851,120 | 100.0% |
| BINARY_OP | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 159,351,560 | 53.5% |
| STORE_SLICE | 138,499,580 | 46.5% |
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
| LOAD_CONST | 27,620,800 | 100.0% |
| BINARY_OP | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 27,619,740 | 100.0% |
| STORE_FAST | 600 | 0.0% |
| STORE_SUBSCR_LIST_INT | 520 | 0.0% |
| STORE_SUBSCR | 20 | 0.0% |


</details>

### BINARY_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 175,997,360 | 72.1% |
| LOAD_FAST_LOAD_FAST | 40,522,320 | 16.6% |
| COPY | 27,619,720 | 11.3% |
| BINARY_SUBSCR | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 161,481,960 | 66.1% |
| LOAD_CONST | 69,754,940 | 28.6% |
| LOAD_FAST | 12,902,620 | 5.3% |


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
| LOAD_CONST | 27,619,720 | 50.0% |
| CALL_BUILTIN_FAST | 27,619,720 | 50.0% |
| CALL | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 27,619,740 | 50.0% |
| CALL_BUILTIN_FAST | 27,619,720 | 50.0% |
| CALL | 20 | 0.0% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 71,453,720 | 56.5% |
| LOAD_CONST | 42,136,080 | 33.3% |
| LOAD_FAST | 12,902,600 | 10.2% |
| COMPARE_OP | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 126,492,580 | 100.0% |


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
| SWAP | 27,619,720 | 100.0% |
| BINARY_OP_SUBTRACT_INT | 520 | 0.0% |
| STORE_SUBSCR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 27,619,740 | 100.0% |
| LOAD_FAST | 540 | 0.0% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 161,481,920 | 100.0% |
| TO_BOOL | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 161,481,960 | 100.0% |


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
|          hit | 325,472,140 | 100.0% |

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
|     deferred | 138,499,720 | 36.2% |
|          hit | 244,139,520 | 63.8% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 120 | 0.4% |
| Failure | 34,020 | 99.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| list slice | 34,020 | 100.0% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 480 | 0.0% |
|          hit | 55,239,840 | 100.0% |

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
|          hit | 126,492,580 | 100.0% |

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
|          hit | 27,620,280 | 100.0% |

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
|          hit | 161,481,960 | 100.0% |

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
| Basic | 2,621,081,720 | 63.2% |
| Not specialized | 588,933,520 | 14.2% |
| Specialized hits | 940,447,040 | 22.7% |
| Specialized misses | 0 | 0.0% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| BINARY_SUBSCR | 138,499,720 | 100.0% |
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
| Interpreter increfs | 958,298,840 | 87.4% |
| Interpreter decrefs | 1,419,763,220 | 91.1% |
| Increfs | 138,500,080 | 12.6% |
| Decrefs | 138,500,281 | 8.9% |
| Materialize dict (on request) | 0 |  |
| Materialize dict (new key) | 0 |  |
| Materialize dict (too big) | 0 |  |
| Materialize dict (str subclass) | 0 |  |
| Dematerialize dict | 0 |  |
| Method cache hits | 205 |  |
| Method cache misses | 35 |  |
| Method cache collisions | 35 |  |
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
| Trace too long | 20 | 25.0% |
| Trace too short | 0 | 0.0% |
| Inner loop found | 40 | 50.0% |
| Recursive call | 0 | 0.0% |
| Traces executed | 171,734,960 |  |
| Uops executed | 2,558,865,220 | 14.90 |

### Trace length histogram

<details>
<summary> trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 0 | 0.0% |
| <= 16 | 20 | 25.0% |
| <= 32 | 0 | 0.0% |
| <= 64 | 20 | 25.0% |
| <= 128 | 40 | 50.0% |


</details>

### Optimized trace length histogram

<details>
<summary> optimized trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 20 | 25.0% |
| <= 16 | 0 | 0.0% |
| <= 32 | 0 | 0.0% |
| <= 64 | 20 | 25.0% |
| <= 128 | 40 | 50.0% |


</details>

### Trace run length histogram

<details>
<summary> trace run length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 130,031,920 | 75.7% |
| <= 16 | 0 | 0.0% |
| <= 32 | 6,874,100 | 4.0% |
| <= 64 | 33,417,980 | 19.5% |
| <= 128 | 1,410,960 | 0.8% |


</details>

### Uop execution stats

<details>
<summary> uop execution stats </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| _SET_IP | 611,770,640 | 23.9% | 23.9% |  |
| LOAD_FAST | 576,202,200 | 22.5% | 46.4% |  |
| LOAD_CONST | 418,435,600 | 16.4% | 62.8% |  |
| _EXIT_TRACE | 171,734,960 | 6.7% | 69.5% |  |
| BUILD_SLICE | 115,516,880 | 4.5% | 74.0% |  |
| COMPARE_OP_INT | 100,972,040 | 3.9% | 77.9% |  |
| BINARY_SUBSCR_LIST_INT | 71,942,200 | 2.8% | 80.8% |  |
| _POP_JUMP_IF_FALSE | 66,277,740 | 2.6% | 83.4% |  |
| _GUARD_BOTH_INT | 63,965,440 | 2.5% | 85.9% |  |
| _BINARY_OP_SUBTRACT_INT | 63,965,440 | 2.5% | 88.4% |  |
| PUSH_NULL | 44,525,120 | 1.7% | 90.1% |  |
| COPY | 44,525,120 | 1.7% | 91.8% |  |
| SWAP | 44,525,120 | 1.7% | 93.6% |  |
| CALL_BUILTIN_FAST | 44,525,120 | 1.7% | 95.3% |  |
| STORE_SUBSCR_LIST_INT | 43,114,000 | 1.7% | 97.0% |  |
| _POP_JUMP_IF_TRUE | 33,753,600 | 1.3% | 98.3% |  |
| POP_TOP | 22,262,560 | 0.9% | 99.2% |  |
| STORE_FAST | 20,851,440 | 0.8% | 100.0% |  |


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>

|Opcode | Count | 
|---|---:|
| BINARY_SUBSCR | 20 |


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
