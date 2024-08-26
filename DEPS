# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': 'ffd454c57bdbea8ae493df7a5d2733ae2b02cb81',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': 'a24a94aa0d1fc4e5556bdf9c6b2afe8eacc55326',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '69ab0f32dc6376d74b3f5b0b7161c6681478badd',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'edc68950bf725edc89b3e1974c533454cf2ae37c',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': 'a6a5dc0d078ade9bde75bd78404462509cbdce99',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '25049cde8bf8b0a8053aec5016472d2874e0ef94',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '7e82aea5fc1394d417a0df6a5680a4cce5c37286',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': '7ea05992a52e96426bd4c56ea12d208e0d6c9a5f',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': 'c3a7a71dd5a9e5ec8a18349180e05b9be4adaacc',
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
