# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '7a47e2531cb334982b2a2dd8513dca0a3de4373d',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': 'd554b6eb885b8b4ebadbad08dec684900e840479',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'b824a462d4256d720bebb40e78b9eb8f78bbb305',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '8a67272ca6c266b21dd0a9548471756a237ebbef',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '2fa203425eb4af9dfc6b03f97ef72b0b5bcb8350',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '052ac24611eced7b0ca62cc5cca2eeeb2051fa28',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '2a3347d5e74d359e3ecb8e229917f3335bfa2dfa',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': 'c010c19e796035e92fb3b0462cb887518a41a7c1',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '4d91ca7887d869e20fcbfd8d38642d783b125ae3',
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
