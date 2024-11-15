# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '4f8fa5f970def61619b4f3810842d5c725650910',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': '4e9bb6f426cf776910848441da65cc14f1146e77',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '45b314049d6262c850cc873c8f9a30f41a1e0c13',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '27433b11e9e9e2738eb34d7dd07694a82fc0b51d',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': 'cbcad3c0587dddc768d76641ea00f5c45ab5a278',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '9959ca313e3a7bee3d6a02b7033fd08c51d06871',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'df2ac1bb61f09a80db979d7108adf07b6fe55913',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': '247accd4ed34bb80c745a9c844a59cdc992bd7e9',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': 'a7639da196fdf5643a81686679fc0cb31d30bb25',
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
