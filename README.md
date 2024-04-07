# quick_secure_storage_patch

Editor: `VS Code`

## Create a new Flutter project


## Open a new terminal in VS Code

## Install flutter_secure_storage:

``` cmd
flutter pub add flutter_secure_storage
```

## Add the flutter_secure_storage import

``` cmd
import 'package:flutter_secure_storage/flutter_secure_storage.dart';
```

## Run windows desktop build
- Project will fail  (thats fine)


## Run the following commands to copy files to where they are needed

``` cmd
cp "windows/flutter/ephemeral/.plugin_symlinks/flutter_secure_storage_windows/windows/*.*" "windows/flutter/ephemeral/"
```

``` cmd
cp "windows/flutter/ephemeral/atls.lib" "build/windows/x64/plugins/flutter_secure_storage_windows/"
```

## Run windows desktop build (twice) ((yes run 2 times))

- And you are done.
