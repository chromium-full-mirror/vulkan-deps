# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '84e166f34f44f37231a6a8c94f2437f76f3bae05',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': '7755d8636b14d7fb5f29d5a67b2180771ebe4382',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '29981f65241605e08b0ede4cfeb999fe3b723c6a',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '502666433f77439bece5b4c5c7e67bff90af2350',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '8d6039a455a7ecc7d2a592ff97f62db4e59b70bf',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '7ab4d368d8499f3366728a6991eec910d9c34ae4',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '6d586e9a4f0d5ffdef862149adaf1ec6b3130182',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': 'c0e15b2c46f9ae2314925cbbe9d97ed6ea8a717d',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '63b0114941e2155c1283ab3afaec455249d41385',
}

deps = {
  'glslang/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/glslang@{glslang_revision}',
  },

  'lunarg-vulkantools/src': {
    'url': '{chromium_git}/external/github.com/LunarG/VulkanTools@{lunarg_vulkantools_revision}',
  },

  'spirv-cross/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Cross@{spirv_cross_revision}',
  },

  'spirv-headers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Headers@{spirv_headers_revision}',
  },

  'spirv-tools/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Tools@{spirv_tools_revision}',
  },

  'vulkan-headers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Headers@{vulkan_headers_revision}',
  },

  'vulkan-loader/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Loader@{vulkan_loader_revision}',
  },

  'vulkan-tools/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Tools@{vulkan_tools_revision}',
  },

  'vulkan-utility-libraries/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Utility-Libraries@{vulkan_utility_libraries_revision}',
  },

  'vulkan-validation-layers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-ValidationLayers@{vulkan_validation_revision}',
  },
}
