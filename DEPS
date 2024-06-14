# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': 'a92c61f8456fa9731c0b000a2c6fc52a740c2be7',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': '27ebab7411bf59f9e9e42a5f6946a03eb9e425b8',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '2acb319af38d43be3ea76bfabf3998e5281d8d12',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'bc28ac7c195f59b14535edec8472d97fd32a91ad',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '05fe2cc910a68c9ba5dac07db46ef78573acee72',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '99a7973d3c4f5413c6c14b2519d0980041cce68f',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'a9a1bcd709e185700847268eb4310f6484b027bc',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': '1b07de9a3a174b853833f7f87a824f20604266b9',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '07029df55126e78a6e3bf1a60aa6a93380baf6fb',
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
