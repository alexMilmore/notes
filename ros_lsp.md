# Getting LSP with ROS

clangd needs compile commands to understand stuff outside the dir
```
colcon build --cmake-args='-DCMAKE_EXPORT_COMPILE_COMMANDS=ON'
```

then symlink it to the repo

