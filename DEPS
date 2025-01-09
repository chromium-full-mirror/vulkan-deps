# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': 'f754c852a87988eb097a39480c65f704ceb46274',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': '73995ddc2b38b5653c8eb3b4a0d1cd6cc2cea4c0',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'a380cd25433092dbce9a455a3feb1242138febee',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '8b39a8b54d55c8737196cdce705f32f94d3b2463',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': 'd4a196d8c84e032d27f999adcea3075517c1c97f',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '369f59ad598b60d6ed9f553af651c5cccd20234c',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '315964ad5aabd5b148a484e5fbea8a365c8d1eb3',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': '5a88b6042edb8f03eefc8de73bd73a899989373f',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '912a1a5a29daf269512edb47a2d55a5aa1145f93',
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
