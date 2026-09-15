# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '81f3df51ab1cf14ea35ff35f921241625cfbd7ca',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': 'e16b61c5601741d5cce4ba1d1564d91a3a31596c',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '04fd3caa1e8267e4d95c806cad901181728e1006',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '25318da789b94854908a15b4c718145e4e63fc87',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': 'ee2ec5fd83dafce291024683b50dc89219333076',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': 'bde79ad2dd832db9180c4a6eca2e84ceb12b1bb0',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '462d9819e5953e064e1dcdc04d3edc5fc6bc9431',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': '930a38bce146cf85c5bd7cb00fa33a66c640c0c6',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '59521d4d5dd68e9a3978902f936921e83fa4f7f0',
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
