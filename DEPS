# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '1c7030f06f356c2bd5d66d71e6b47f92eae8138e',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': '2ff9b59f5b9ac22644e391fb64ec372018440502',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '0ff65315141cf745c1ac286084943409edbe6504',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'cf9d8e2d0061269947c49214471f7848c02c8ed9',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '3dda5a1a87b62fdf3baf4680edc41c00e85a7a22',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': 'd03e5159590351a04673e6451ea467fdb26ee85e',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '8e9daf5dd62ff81ba67a1c20dad64ee87f21005e',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': 'b861e607ec1e31dcd66133918bf9d6bd22da3c02',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '5b56b3ebddca0a9934d2a0bbd687c37826de0e0c',
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
