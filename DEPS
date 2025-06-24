# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': 'efd24d75bcbc55620e759f6bf42c45a32abac5f8',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': '8e3261f207f1c520522be2021cf364ebb1bad3f0',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '9e3836d7d6023843a72ecd3fbf3f09b1b6747a9e',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '33e02568181e3312f49a3cf33df470bf96ef293a',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '10739e8e00a7b6f74d22dd0a547f1406ff1f5eb9',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '342da33fdec78d269657194c9082835d647d2e68',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'e3fc64396755191b3c51e5c57d0454872e7fa487',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': '72665ee1e50db3d949080df8d727dffa8067f5f8',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '6016c4624f8ad3df64987936bfbeb29f32da2d55',
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
