# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '455fb86658e98f8eb7d7a1b3980a0524a05160eb',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': '031011bb2a278a972b0b457e15cb077ae98434cf',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '0a7f626a6ae86284a413d105b47a6fb413bf6c92',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '91ac969ed599bfd0697a5b88cfae550318a04392',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '450bd2232225d6c7728a4108055ac2e37cef6475',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '69e84021a1f5912706f94dd8ff3bf217d780398e',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'e8a4ce73f3244d814ccc84e723bb0442fab4dcf7',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': '9a3f4105c16bde4e2717eeab0fcc5a49236f7294',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '10b81cbe9a0db05f0a332cd8fdcc0ac5d5871a6b',
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
