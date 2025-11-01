# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': 'ffcdd3ea9acf4fd70746250731e93c6c73f1cba3',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': 'cc96b2c7a248ba1e09cd59f2a1c39af56674b000',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'f2e4bd213104fe323a01e935df56557328d37ac8',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '6570fd4076d3f6ba7e1349af042d9f97f7378884',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '766aaabe571fa32c53606085775340b78ab8d728',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '6f557a4ff7dfc0f5eb58eb1f492d3d3de723b6c4',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '5f090a13d0629694036efb104f8633af69ba3ce7',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': 'cd5b255b5c1932797bbf552c6773d9aa44f800f7',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '6ef93f1d8603e2a9dcf83f9ca5d72394ac3b226a',
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
