# local-dynamodb-js

## 0.0.4

### Patch Changes

- 58cb116: Cleaned up the TS docs, and added in new functions to the localDynamodDb setup. You can now get the set port or mode, along with re confgure your container options and restart it. also provided some liveness and readiness checks. Lastly gave user a status helper with basic information, and wrote some tests. Need to figure out workspaces so i can add in example.

## 0.0.3

### Patch Changes

- 4eca8b7: the publish was not generating the types should have caught this locally. big bumg. Now on v0.0.3 for no reason lol. Anyways should be all good now, we can cleanup versoin later

## 0.0.2

### Patch Changes

- 6d9b82c: The build before was not exporting members correctly. This should fix the build script. Should have sent to a beta tag, whatever.

## 0.0.1

### Patch Changes

- 1aa59a8: Initial release of LocalDynamoDb to npm. It contains the bare basic functionality needed in order to use the local dynamodb container. A user can at this point start() and stop() a container. And the start() handles the downloading of the local client unless the user tells us to use a local jar.
