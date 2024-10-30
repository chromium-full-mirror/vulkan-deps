# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '63ebbe367c8c219e262a2bf78b7395b74cc9d9af',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': 'a251560a3f1ea56fb5b1d32667d2df6e83e06eda',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'cb6b2c32dbfc3257c1e9142a116fe9ee3d9b80a2',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '5f1e86cb55c48949d8a25eb8e03e6930c4179ed9',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': 'f2eb740f3f0340ad941e563484d5ba45a5ec6af0',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '7a83084ef84cc0d47c31d2872a4939c4c59186a1',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'e94085e2167e33b6b18474da24ff18f46bc56976',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': '9123b8c04b378c1b81899314e3060a80f255a24b',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '9d934c925b9b8f4dc629a36967218327979d50fb',
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
