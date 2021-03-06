# IBlockAccess

BlockAccess objects are a group of blocks accessible via coordinates. They mainly serves as superinterface to [IWorld](/Vanilla/World/IWorld/), that means all these functions are also available to all [IWorld](/Vanilla/World/IWorld/) objects.

## 导入类

It might be required to [import](/AdvancedFunctions/Import/) the class to avoid errors.  
`import crafttweaker.world.IBlockAccess`

## ZenMethods

### Get or Set a blockState at a specific Position

Use an [IBlockPos](/Vanilla/World/IBlockPos/) Object and an [IBlockState](/Vanilla/Blocks/IBlockState/) Object.  
Returns an [IBlockState](/Vanilla/Blocks/IBlockState/).

```zenscript
accObj.getBlockState(IBlockPos pos);
```

### Check if a block is an air block.

Use an [IBlockPos](/Vanilla/World/IBlockPos/) object.  
Returns a bool.

```zenscript
accObj.isAirBlock(IBlockPos pos);
```

### Get strong Power at a block's side

Use an [IBlockPos](/Vanilla/World/IBlockPos/) object and an [IFacing](/Vanilla/World/IFacing/) object.  
Returns an int.

```zenscript
accObj.getStrongPower(BlockPos var1, EnumFacing var2);
```