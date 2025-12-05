# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '19246e3fbc095586e0e325b378ea351aababeb7c',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': '031011bb2a278a972b0b457e15cb077ae98434cf',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '6146b3d9ad4fcc5fb512209d348e97ce03749169',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '8c1e6ca9b896a5a82ea39973a2f677f515f1f45d',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '2fa203425eb4af9dfc6b03f97ef72b0b5bcb8350',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '0db9a0d55e33f8b63b733f37dc59eb441d51abf0',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '8542e6dcfc6daef20d561220f1d91a02c25d95b2',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': 'c010c19e796035e92fb3b0462cb887518a41a7c1',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '6dbf6cf2870e5c00c235614ce51a3e4a70bfdb46',
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
