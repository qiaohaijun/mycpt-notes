```c++
// 生成一个空的数据
PipelineManager::NewPipeTask();
```

### 重要数据结构
```cpp
std::vector<PipeInterface*> pipe_vec_;
// pipe_name
std::map<string, PipeInterface*> pipe_map;
```

