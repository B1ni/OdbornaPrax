# OdbornaPrax
Odborna Prax - Siemens Healthineers

how to include dll:

create /libs folder in your main project repository
there copy selected .dll file

in c# projekt than include this

<ItemGroup>
  <Reference Include="API">
    <HintPath>libs\API</HintPath>
  </Reference>
</ItemGroup>
