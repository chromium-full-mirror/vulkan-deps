# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '1062752a891c95b2bfeed9e356562d88f9df84ac',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': '70c6ba3d70dc038cc1fcf319fa2ea46b8edc5d3b',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '3f17b2af6784bfa2c5aa5dbb8e0e74a607dd8b3b',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '7cac4f3551b177ebc32aa58d47e3a5ce734f160f',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '6a74a7d65cafa19e38ec116651436cce6efd5b2e',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '037ed53cffefd8e58f3223b47c5ec69bec0d4857',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '2744de9936755fea6912d47e7a0a8857d8a4fdee',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': '160e946f5d4b3a657f47b7fc4b0bd3cc8d0d6afd',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': 'cf3372f90d354d2c824de503a591b3d0afe3b6fd',
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
