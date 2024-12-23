# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '3a2834e7702651043ca9f35d022739e740563516',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': '73995ddc2b38b5653c8eb3b4a0d1cd6cc2cea4c0',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '3f17b2af6784bfa2c5aa5dbb8e0e74a607dd8b3b',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '9295a8b94ed0751565fa9cda6d949f5e388b32d9',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': 'd4a196d8c84e032d27f999adcea3075517c1c97f',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '6a6878c614c8c6dbe81ee7a9f1176bdb52dc7dd7',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'a71347ae4d76eb8454459373d4e1bfb929ea6a89',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': '5a88b6042edb8f03eefc8de73bd73a899989373f',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '6affd2ae0d363eb65ec28762b1f43c09fb5b88cc',
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
