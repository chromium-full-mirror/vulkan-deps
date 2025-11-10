# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': 'b58249a96fce25cce5d440b265b58fead80d1377',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': '2a089520f7d5f5107160a9318e5ed1b757159519',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '0ff65315141cf745c1ac286084943409edbe6504',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '5a7edbe46ac96121ff5ed53878376584a8b3d5ba',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '3dda5a1a87b62fdf3baf4680edc41c00e85a7a22',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': 'd03e5159590351a04673e6451ea467fdb26ee85e',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '8e9daf5dd62ff81ba67a1c20dad64ee87f21005e',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': 'b861e607ec1e31dcd66133918bf9d6bd22da3c02',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '483062e6990ed7bcea3bb3c3eed4950ec62038ab',
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
