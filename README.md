- 👋 Hi, I’m @2247984540
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
2247984540/2247984540 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

```mermaid
graph TD;
    subgraph device [块设备 (Block Device)]
        direction LR;
        A[块 0<br/><b>超级块 (SuperBlock)</b><br/><i>存储文件系统元数据</i>] --> B;
        B[块 1 ...<br/><b>Inode 位图 (Inode Bitmap)</b><br/><i>标记 Inode 是否被占用</i>] --> C;
        C[...] --> D[块 M ...<br/><b>Inode 区域 (Inode Area)</b><br/><i>存储所有 Inode 结构体</i>] --> E;
        E[...] --> F[块 N ...<br/><b>数据位图 (Data Bitmap)</b><br/><i>标记数据块是否被占用</i>] --> G;
        G[...] --> H[块 P ...<br/><b>数据区域 (Data Area)</b><br/><i>存储文件和目录的实际内容</i>] --> I;
        I[...]
    end
```
