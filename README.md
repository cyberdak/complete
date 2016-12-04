# complete

58同城 RPC 框架 SCF 的补全脚本

### 使用方法
将脚本下载到 /etc/bash_completion.d/ 中,然后依次执行一下命令

```
# source scf_comptele
# complete -F scf_complete scf
# complete -F scf_complete /opt/scf/bin/scf
```

source 只针对本次 session，永久的方法，可以将以上语句写入到 `~/.bashrc` 中.
