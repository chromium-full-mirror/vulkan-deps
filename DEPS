# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '385445a87d21d7a5c7bee2f7bef8a87850f6bf28',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': 'f3353fc09adcf02a6524e2101c0ee2c17d91a140',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '5c6004e758e0c80185ef2cee93ae5c10fa342a5b',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '3e73ae769e684f17b283250f803a231a830d45e3',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': 'b26454f3ccd67e704117a39295fa13935fd3804c',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '0b137080f608a1f99527f1b123424545f2d9ba49',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '1d3fbab1ff5abce9f3eb9f3e7fcf66f455ae4475',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': '5a873d3b75d38ef6a0833589ce3603d63f3f6a9c',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': 'd63b17612002fdbf0ba08d12b1574b8f422a70f0',
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
