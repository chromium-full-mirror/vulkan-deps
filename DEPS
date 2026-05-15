# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '605c7f67fb470aecf6ee7d5a660c765e11065a9e',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': 'e1f872619095e51d3f310be320e77347de1158d4',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'aaffbc59b41bf8faea671b0d1c6b34a584c45171',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '860c90a8bbd9b4233daadb3667d81f69d20f7541',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '015e25c3c91b70eb1a754d36fb14c4ba6ad9b0b9',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': 'ebc06b83174f6b5200eb21de3e83fc0d03ddcd18',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '822a2d8efb2ec261295bf40bd17b60252823b459',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': '28d3b5930a6da0e4f15040679d8b51dda0b29c86',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': 'd24e2c2845da90f39323b9f4bec9bb83ea20e7d6',
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
