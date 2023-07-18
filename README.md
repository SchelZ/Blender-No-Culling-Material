import bpy

for mat in bpy.data.materials:
    bpy.data.materials[str(mat.name)].use_backface_culling = False
