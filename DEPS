# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': 'efa016659ffc4f2ae566b6b1db71a70655ac33a1',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': '9c4c1717c76503f9b9f0412af365ebde65ffcd60',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '496543121ce6419f23d6fa5d7194ba66c36212d2',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'fd9bc85c546219b61b04556695c17f4ac3a4192a',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': 'ee2ec5fd83dafce291024683b50dc89219333076',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': 'b8b96a2862bff1eed468e602d43f706beae89cf1',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'af0452ed9eedc16acbe58ef378177057d67a8d84',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': '2176ec8c5f5d2272161277ab96fe5b8f7633113e',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '8e31a45dfff17c9284641dce24d0d8da9ad7c6db',
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
