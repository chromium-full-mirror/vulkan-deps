# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '8ea9298b276e5dc528e0699c256b8b519cfb322f',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': 'a251560a3f1ea56fb5b1d32667d2df6e83e06eda',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '252dc2df08f58e0e50c8437edc0e77eacdfb7559',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '895bb9ffecc2c48646b50f77aeb85f5b70b9bb37',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': 'b955ae0edb4f02074bfbf134ccc1980e83122d30',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '2d2d46f38fb2e8c0362668ca3605f81d71236f68',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '2030a5b09f5656d1e9b8c9c4ab3ebe98024da150',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': 'b541be2eae6f22772015dc76d215c723693ae028',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '8027ac19150ab5479fa220444a98b0ffffeed160',
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
