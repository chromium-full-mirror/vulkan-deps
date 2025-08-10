# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': 'b4e66d7b148ea1c245e1a66c2f3abf6c1103fc59',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': '7d91d6f4df4e32fda3021e2923be7f92140d31c4',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'a7361efd139bf65de0e86d43b01b01e0b34d387f',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '5e7108e11015b1e2c7d944f766524d19fb599b9d',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '2e0a6e699e35c9609bde2ca4abb0d380c0378639',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': 'be3fe40144f269d0e834693f966443c6c24a6962',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'f766b30b2de3ffe2cf6b656d943720882617ec58',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': '4f4c0b6c61223b703f1c753a404578d7d63932ad',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '3218d4c9923db10e1184701e970b993e2588b334',
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
