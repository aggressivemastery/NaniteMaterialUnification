# NaniteMaterialUnification
Demonstration of using PerInstanceCustomData and CustomPrimititiveData to drive texture selection within a single master material. This enabled the possibility of a single draw call for a Nanite Mesh and All Materials on it.

VIDEO DEMONSTRATION OF BASE CODE https://youtu.be/oSxfBiIc_zw

GameDevMicah Berninghausen of Aggressive Mastery demonstrates the use of a combined material to reduce draw calls in UNREAL ENGINE 5 and UEFN / FORNITE Games.

All Actor Components have the ability to store a "Custom Primitive Data" value that can be used by logic with-in a material graph to select textures. This can also be done with "PER Instance Custom Data" on Instanced Static Mesh Components. 

The advantage to combined textures into a single material is reduced draw calls to the GPU, but it carries the additional cost that unused textures always remain loaded into VRAM and RAM when the material is used. 

For environments that can count on specific textures always being loaded into VRAM, like RED vs BLUE themed worlds, this optimization may work best!

Micah Berninghausen is presenting at Unreal Fest ORLAND 2025. Check them out streamed or in person!
UEFN Static Level Optimizations and a Second talk on Nanite Niagara Destruction "Speeding Up Destruction in the Giantess Playground"

Download this sample project on GITHUB at : 
https://github.com/aggressivemastery/NaniteMaterialUnification
and AggressiveMastery.com

Cheers,
Micah
