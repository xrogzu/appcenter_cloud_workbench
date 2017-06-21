#  权限管理

## 功能概述

权限管理是在权限组件进行扩展开发的，提供用户管理、角色管理、授权管理等功能，另外还提供访问控制、加密、会话管理、缓存等功能。权限管理主要解决授权和访问控制问题，以控制用户在应用系统中对受保护资源是否拥有相应的访问权限和相应的操作权限。权限组件提供了扩展开发框架供开发者按照自己的具体权限需求进行扩展。下图是权限组件的功能架构，以及授权和访问控制的过程。

在工作台里权限管理主要提供用户、角色管理与小部件、小应用授权。

## 界面说明

如【图3.2管理中心主界面】所示。权限管理主要分为四个部分，分别是用户管理、角色管理、小部件授权和小应用授权。

### 用户管理

如【图3.7用户管理主界面】，界面上方提供功能框与搜索框，支持单用户/多用户管理与搜索操作。下方按行显示具体用户的具体信息，并在最左端提供勾选按钮，在最右端提供状态显示。

针对单个用户，还提供【图3.8单用户管理功能框】，支持单用户信息编辑、密码重置、停用/启用与删除功能。

![](/articles/workbench/3-/image/image12.png)

图3.3 5用户管理主界面

![](/articles/workbench/3-/image/image13.png)

图3.3 6单用户管理功能框

### 角色管理

如【图3.9角色管理主界面】，界面主要分为两个部分，左半部分是角色清单，右半部分是关联/未关联用户清单，并提供新增、编辑、删除角色以及搜索、关联/取消管理用户功能。

![](/articles/workbench/3-/image/image14.png)

图3.3 7角色管理主界面

### 小部件授权

界面分为左右两部分，左边显示的角色清单，右边显示的角色已经授权的小部件，如【图3.10小部件授权主界面】。

角色清单中显示角色名称，角色编码，能对每个角色进行小部件授权，显示每个角色已经授权的小部件清单；已经授权的小部件清单显示小部件分组，小部件名称，小部件编码。

![](/articles/workbench/3-/image/image15.png)

图3.3 8小部件授权主界面

### 小应用授权

![](/articles/workbench/3-/image/image16.png)

图3.3 9小应用授权主界面

界面分为左右两部分，左边显示的角色清单，右边显示的角色已经授权的小应用，如【图3.11小应用授权主界面】。

角色清单中显示角色名称，角色编码，能对每个角色进行小应用授权，显示每个角色已经授权的小应用清单；已经授权的小应用清单显示小应用领域，小应用分组，小部件应用名称。

## 关键操作

用户管理、角色管理、小部件授权和小应用授权的操作流程如下。

### 用户管理

用户管理支持所有已有用户的用户名、账号、邮箱、注册时间、手机号、来源、授权应用名称及是否启用状态的显示，提供用户管理，可以新增，停用，启用，导入，导出，修改，删除用户，并提供重置密码功能。

用户管理具体功能的操作流程如下。

1.新增

单击上方功能菜单栏中【新增】创建新用户，账号、手机号、用户名为必填信息，邮箱为选填信息，单击【完成】完成新用户建立。

2.停用

**批量停用**：勾选多个启用状态用户前的勾选框，单击上方功能菜单栏【停用】批量停用用户。

**单用户停用**：点击单个启用状态用户右下方的侧拉按钮，单击【停用】停用该用户。

3.启用

**批量启用**：勾选多个停用状态用户前的勾选框，单击上方功能菜单栏【启用】批量启用用户。

**单用户启用**：点击单个停用状态用户右下方的侧拉按钮，单击【启用】启用该用户。

4.导入

单击上方功能菜单栏【导入】以导入本地用户。

5.导出

单击上方功能菜单栏【导出】，在下拉菜单中选择【导出当前页】或【导出全部】的所有用户。

6.删除

**批量删除**：勾选多个用户前的勾选框，单击上方功能菜单栏【删除】批量删除用户。

**单用户删除**：点击单个用户右下方的侧拉按钮，单击【删除】删除该用户。

7.密码重置

点击单个用户右下方的侧拉按钮，单击【密码重置】→【确认】，重置该用户密码。

8.编辑

![](/articles/workbench/3-/image/image17.png)

图3.3 10用户信息编辑

点击单个用户右下方的侧拉按钮，单击【编辑】可进入编辑状态，修改该用户的用户名、邮箱和手机号的具体信息。

9.搜索框

上方功能菜单栏最右侧提供搜索框，输入用户账号的关键字母，搜索结果为匹配用户列表。

单击左上方【返回】，返回管理中心。

### 角色管理

支持角色与角色相关联的用户显示、管理。角色管理可以进行角色的新增，修改，删除，并能与用户进行关联和取消关联。具体操作如下。

1.新增角色

![](/articles/workbench/3-/image/image18.png)

图3.3 11新增角色

单击新增角色图标，添加用户编码、用户名称，单击勾号完成增添新角色。

2.修改角色

选定已有角色，单击右边的编辑按钮，可以对用户编码和用户名称进行修改。

3.删除角色

选定已有角色，单击右边的删除按钮，删除该用户。

4.角色关联状态

已关联用户的角色会在角色最右方显示关联图标。

5.关联用户

![](/articles/workbench/3-/image/image19.png)



单击已有角色，选定右方已关联/未关联清单的【未关联】清单，选择要关联的用户，单击最右方【关联】完成用户关联。

6.取消关联用户

![](/articles/workbench/3-/image/image20.png)

图3.3 13取消关联用户

单击已有角色，选定右方已关联/未关联清单的【已关联】清单，选择要取消关联的用户，单击最右方【取消关联】完成取消用户关联。

7.搜索框

已关联/未关联清单右上方提供搜索框，输入用户账号的关键字母，可以在该角色的已关联/未关联用户中进行匹配搜索。

单击左上方【返回】，返回管理中心。

### 小部件授权

小部件授权支持对角色进行小部件授权。

![](/articles/workbench/3-/image/image21.png)

图3.3 14给角色授权小部件

单击【授权】，进入小部件授权子页面，如【图3.16给角色授权小部件】，默认显示所有小部件。

**小部件分组**：上方左侧的下拉列表可以按照不同分组过滤小部件。

**小部件搜索**：上方右侧的搜索框可以匹配关键字母搜索小部件。

**小部件授权状态**：每个小部件下方的方框中显示已勾选的，表示该某个小部件是否已经授权。

**授权与取消授权**：在每个小部件下方的方框中勾选或者取消勾选，点击最右方【保存】后完成授权并返回小部件授权列表页面。

单击左上方【返回】，返回管理中心。

### 小应用授权

小应用授权支持对角色进行小应用授权。

![](/articles/workbench/3-/image/image22.png)

图3.3 15给角色授权小应用

单击【授权】，进入小应用授权子页面，如【图3.17给角色授权小应用】，默认显示所有小应用。

**小应用领域**：上方左侧的下拉列表可以按照不同领域过滤小应用。

**小应用分组**：上方右侧的下拉列表可以按照不同分组过滤小应用。

**小应用授权状态**：每个小应用下方的方框中显示已勾选的，表示该某个小应用是否已经授权。

**授权与取消授权**：在每个小应用下方的方框中勾选或者取消勾选，点击【保存】后完成授权并返回小应用授权列表页面。

单击左上方【返回】，返回管理中心。
