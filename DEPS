# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '21b4e37133868b3a50ef15fc027ecd6d3a52c875',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': 'da60ac4327af194dfa773a07db6cd5d5aaa6848d',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '2a611a970fdbc41ac2e3e328802aed9985352dca',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '108b19e5c6979f496deffad4acbe354237afa7d3',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '10739e8e00a7b6f74d22dd0a547f1406ff1f5eb9',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '342da33fdec78d269657194c9082835d647d2e68',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'e3fc64396755191b3c51e5c57d0454872e7fa487',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': '72665ee1e50db3d949080df8d727dffa8067f5f8',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': 'e086a717059f54c94d090998628250ae8f238fd6',
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
