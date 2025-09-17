
!!! warning "Documentation In Progress"

    This documentation is in its early stages and is far from complete.

## Overview

!!! info inline end "Blueprint and C++"

    Knowledge of C++ is ***NOT required*** to leverage the capabilities of this plugin.
The Anim Tools plugin[^1] is a powerful framework for programmatically processing and modifying `UAnimSequence` assets within the Unreal Engine. 


Some of the key features are listed below.

- **Bulk Animation Processing**: Modify multiple AnimSequences at once.
- **Custom Operations**: Create user-defined Operations (`UATBaseOperation`) in either C++ or Blueprint.
- **Non-Destructive Workflow**: Preview changes before applying them and choose whether to overwrite existing assets or generate new ones.
- **Per-Animation Property Control**: Configure Operation properties differently for each AnimSequence.

## Quick-Start Guide

1. **Create a Database**. Right-click in the Content Browser, select Anim Tools, then click on ATDatabase. Name the asset appropriately, then double-click on it to open it.




[^1]: Previously named MoCap Tools (MCT).
