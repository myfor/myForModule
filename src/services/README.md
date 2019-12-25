# SnackBar 提示框

## Usage
将 SnackBarService 服务注入
调用 open();
open('提示信息', 2000<提示框持续毫秒>);
```typescript
constructor(private snack: SnackBarService) { }
this.snack.open('提示');
```