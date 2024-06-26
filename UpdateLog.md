# 1.5REALEASE

1. 检测修复

   - 同步RSC1.4SNAPSHOT

# 1.5SHOT

1. 检测修复

   - 现在是先检查`mob_drops.yml`再检查`geo_resources.yml`了
   - 增加了`supers.yml`和`foods.yml`的检查
   - 删除了在最后检查任何错误的catch

2. Bug修复

   - 修复了不能检查多个addon的Bug

# 1.4REALEASE

1. 同步RSC1.4

# 1.4SHOT

1. 检测删除

   - 删除了**研究**的`name`的检查

# 1.3REALEASE

1. 检测增加

   - 增加了**菜单**的`slots`里的**键的类型**的检测
   - 增加了**研究**的`name`的检查

2. Bug修复
   - 增加了**配方机器**中可选参数`speed`的默认值
   - 删除了**配方机器**中的**输出物品**的位置的检查及其错误的**错误提示信息**
   - 修改了分类检查时**默认**的`tier`的值
   - 修改了**分类**可能错误时的**错误提示信息**
   - 修改了**盔甲的药水效果**的配置检查，以兼容`更新的RSC`
   - 修改了**菜单**里**引用的机器菜单**可能错误时的**错误提示信息**
   - 修改了**材料生成器**里**输出的物品的数量超过最大堆叠**时的提示等级，由`ERROR`改为了`WARN`
   - 修复了当 `material_type` 为 `none` 时，仍然检查 `material` 和 `amount` 的问题
   - 修复了**菜单**的`slots`不是有效的键时，**错误提示信息**错误的问题
   - 修复了当**配方机器**的**配方中的内容**错误时，**错误提示信息**错误的问题
   - 修复了**配方机器**中的`capacity`参数的范围下限错误的问题
   - 修复了**研究**中的`levelCost`与`currencyCost`的检查可能失败的问题
   - 修复了无法正常获取`saveditems`文件夹的问题
   - 修复了`machines.yml`检查顺序错误的问题

3. 源代码

   - 将`missing`变量的名字改为了`null`
   - ~~修改了`finally`块中的代码~~

# 1.3SHOT

1. 检测增加

   - `胸甲检查类型`增加了**鞘翅**

2. Bug修复

   - 修复了盔甲类型检查的错误
   - 修复了对`lateInit:true`的配置的运行顺序的错误

# 1.2REALEASE

1. Bug修复

   - 修复了单槽配方检查的错误

# 1.2SHOT

1. 检测增加

   - 增加了对**RSC 1.3.3**的支持

2. 多文件检查更新

   - 现在此压缩包需解压到 `plugins/RykenSlimeCustomizer/addons`
   - 而不是`plugins/RykenSlimeCustomizer/addons/example`了

3. 配置文件更新

   - 更新了对多文件检查的支持

4. 源代码

   - 优化了源代码质量

# 1.1REALEASE

1. Bug 修复

   - 修复了部分参数的范围检测

# 1.1SHOT

1. Bug 修复

   - 修复了当物品的 `recipe` 的编号不是**数字**时，提示错误的问题
   - 删去了**多余**的检查及其配置 ( `checkPerhapedRecipeType` )

2. README 更新

   - 修改了部分文本
