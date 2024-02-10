Integration between angular and qwik involves large amount of dependencies and sometimes something is not working properly with a weird undebuggable error. This document describes some of them and possible reasons

## NG0203: inject() must be called from an injection context

This can be caused by a mismatch between the version of @angular/_ packages and the version @qwikdev/qwik-angular depends on. Typically, you'd see `node_modules/@angular/_`packages along with`node_modules/@qwikdev/qwik-angular/node_modules/@angular/\*`
