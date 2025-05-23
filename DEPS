# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '93231001597dad1149a5d035af30eda50b9e6b6c',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': '67b5d1d7f84660ca14951315afb4f9baa08ae138',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'c9aad99f9276817f18f72a4696239237c83cb775',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '01021466b5e71deaac9054f56082566c782bfd51',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '75ad707a587e1469fb53a901b9b68fe9f6fbc11f',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': 'c913466fdc5004584890f89ff91121bdb2ffd4ba',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '60b640cb931814fcc6dabe4fc61f4738c56579f6',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': 'ae56bd6e65d9faa731150e931cb35f0d895223bc',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '2cfeb90c13053a5003a8d5a2ee66fee4a0e0cdce',
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
