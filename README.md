# quick_secure_storage_patch

#install flutter_secure_storage:

```
flutter pub add flutter_secure_storage
```

# add import

```
import 'package:flutter_secure_storage/flutter_secure_storage.dart';
```

# run windows desktop build
- project will fail  (thats fine)


- Run commands to copy files to where they are needed

```
cp "windows/flutter/ephemeral/.plugin_symlinks/flutter_secure_storage_windows/windows/*.*" "windows/flutter/ephemeral/"
```

```
cp "windows/flutter/ephemeral/atls.lib" "build/windows/x64/plugins/flutter_secure_storage_windows/"
```

# run windows desktop build (twice) ((yes run 2 times))
- And you are done.

