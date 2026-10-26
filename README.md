# SP2-Missile-Telemetry
这是一个面向 SimplePlanes 2 的导弹遥测工具。它会实时显示每一枚已发射导弹的真实飞行状态——速度、马赫、高度、加速度与过载、航迹/机体转向率、动能、发动机与制导状态——并把每个物理帧写入 CSV，方便事后复盘。

附带可拖拽的实时面板、可多通道叠加的飞行曲线、动能/势能/机械能分析，以及游戏内的历史记录回放：不用重新发射就能查看上一场飞行。界面支持中英双语。

插件只读取游戏数据，不修改 Game.dll、不修改制导、推力、阻力与存档，卸载即恢复原样。仓库同时提供一个独立可选的 MaxSpeed 上限修补插件，用于对比"速度被强制维持"与"严格上限"两种行为。


Missile telemetry for SimplePlanes 2. It shows the real flight state of every launched missile — speed, Mach, altitude, acceleration and G-load, flight-path and body turn rates, kinetic energy, engine and guidance state — and writes every physics step to CSV for later analysis.

It ships with draggable live panels, multi-channel flight graphs, a kinetic/potential/mechanical energy breakdown, and in-game playback of recorded flights, so you can review a sortie without firing another missile. The UI is bilingual (Chinese / English).

Everything is read-only: no changes to Game.dll, guidance, thrust, drag or save files, and uninstalling leaves no trace. The repository also offers an optional companion that turns MaxSpeed into a strict cap, for comparing "speed held at the limit" against "speed free to decay".
