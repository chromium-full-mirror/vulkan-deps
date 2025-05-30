# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': 'be4ee7d0e3bfd151bfda7b3a8e03f8c49c55ed7b',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': '4841ea0a48c4ea07e9f24db3322f31541a25a101',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '7168a5ad041f6b6b9170f027c7417f98a2056ff0',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'c3c5427ec9e5983633199eaab9c6a392ba3a107a',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '75ad707a587e1469fb53a901b9b68fe9f6fbc11f',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': 'c913466fdc5004584890f89ff91121bdb2ffd4ba',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '60b640cb931814fcc6dabe4fc61f4738c56579f6',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': '49ac28931f28bffaa3cd73dc4ad997284d574962',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '5d290c271882a7c06f9b36ce1f879a69a5f95bc5',
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
