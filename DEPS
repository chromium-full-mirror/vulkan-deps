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
  'lunarg_vulkantools_revision': '86d4caaa7b4d3f261c054464276328b2f998fb29',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '6146b3d9ad4fcc5fb512209d348e97ce03749169',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '3e36d0af6f2ad0bc7f870fdf4234b9e4477cd1d4',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '2fa203425eb4af9dfc6b03f97ef72b0b5bcb8350',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '918e869d4eb54a2fbe78546f4931f1ff9e9454bf',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '48b5d246b2d0b1a41ee7ea1b69525ae7bb38a2ae',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': 'c010c19e796035e92fb3b0462cb887518a41a7c1',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '5e6c6bd96224c1c0bb73414a9227d93f7cc236b0',
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
