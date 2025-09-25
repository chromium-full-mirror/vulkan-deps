# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': 'd213562e35573012b6348b2d584457c3704ac09b',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': 'a0d2ebbf72b1120a2119de53d569b31c56af8ba1',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '01e0577914a75a2569c846778c2f93aa8e6feddd',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '19042c8921f35f7bec56b9e5c96c5f5691588ca8',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': 'd7a7044334ad88485c0a6113d1bf51520ac9e541',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '6ec5a0d91c253c6374701e142a95a0d3215bf5a7',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'e3ecc39da57a5ed15ec8de67f136273ee54b78be',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': '23081f01cdee214226bfed5aedd37f092fa55dd9',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '681e1f4c999d21871be06bea85fe868eda6aeb94',
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
