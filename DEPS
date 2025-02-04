# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '1b65bd602b23d401d1c4c86dfa90a36a52c66294',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': '5728a66537b23986135f50c465fcb282b0434da4',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'e7294a8ebed84f8c5bd3686c68dbe12a4e65b644',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'd59325f379ee95217a200122374549cace9d3708',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '39f924b810e561fd86b2558b6711ca68d4363f68',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '30aa753eea24da31cce2701d6957640a122caffa',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'c52931f012cb7b48e42bbf2050a7fb2183b76406',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': 'fe7a09b13899c5c77d956fa310286f7a7eb2c4ed',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': 'e4c80027a14292bca2d2af9f9e11d989e9d0280c',
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
