# ZLUDA
LUDA is a compatibility layer that allows you to run CUDA applications on AMD GPUs by translating CUDA calls into ROCm (Radeon Open Compute) calls. This enables users with AMD GPUs to leverage software that was originally designed for NVIDIA GPUs, such as Blender for GPU-accelerated rendering.

If you want to use ZLUDA with Blender follow these steps:

Step 1:Download ZLUDA: Download the latest release.
Step 2:Extract the Files: Extract the ZLUDA files to a directory of your choice.
Step 3:Locate blender.exe: Find the path to blender.exe in your Blender installation directory Not blender-launcher.exe.
Step 4: Verify ZLUDA is Working
  Open Blender and go to Edit > Preferences > System.
  Under the Cycles Render Devices section, check if your AMD GPU is listed and select it.
  Render a scene to confirm that Blender is using your AMD GPU via ZLUDA.
