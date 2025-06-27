# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '95e6e51a2430185af06a92049395144a6f63a8e1',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': '7d17a4c1bc1d631df60f7a5ada7892cf276f4bdd',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '04b76709bf40a7ce8df3382060ef3620f19de566',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '40eb301f320e1d85ce3bc12798022149eae3eee3',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '16cedde3564629c43808401ad1eb3ca6ef24709a',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '342da33fdec78d269657194c9082835d647d2e68',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'e3fc64396755191b3c51e5c57d0454872e7fa487',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': '72665ee1e50db3d949080df8d727dffa8067f5f8',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '68e4cdd8269c2af39aa16793c9089d1893eae972',
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
