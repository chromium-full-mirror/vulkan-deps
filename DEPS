# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '3454c3618be8754cb2cec77dc21b142121dc606a',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': 'a251560a3f1ea56fb5b1d32667d2df6e83e06eda',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '22c4d1b1e9d1c7d9aa5086c93e6491f21080019b',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'ce92630396c2fd2d6d04819369116af4fb141a28',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': 'ab1ea9059d75b42a5717c7ab55713bdf194ccf21',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': 'c21cdf42bd0ae076d4d200337b9c0f6aa0481f8c',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '9e1ba445cb9ef5267c6062e91c2fa978b1771ba6',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': 'dcb6173f7463ed233696e18eb9992cbe11262af0',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '9182843530aafc0e842317c4befbe6eab0415ec4',
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
