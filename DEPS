# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '23076b376e06a99b4c765df5c9836d127c8bbbfc',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': '61ed60b587759a54c90846b32426fb7355877819',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '496543121ce6419f23d6fa5d7194ba66c36212d2',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'b964f44901ad6396d3b46307ef1ce66eaef3bb83',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': 'b51f6b865c18fc5b33990d12f75e8dfd672cede6',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '0104fa40a160c12cd329a59f6c99e8a54de26a4b',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'f1ea0db666b87e84e7db2268dcfefac0bba4694a',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': '245b48c522b5375c0acd5377d52bef5e4917f31e',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '96f4670ba73b6adc79f94988ef840d16b4418e11',
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
