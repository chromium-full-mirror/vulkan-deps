# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '83bc342ad741773f1ec12a591d845b7cac6e95ab',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': '90a94883608374c606fe52f21a13bbecb6fcd11c',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '04fd3caa1e8267e4d95c806cad901181728e1006',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '4bbc4f1ea60d0907c9ee3f9597539bfec1b04d24',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': 'ee2ec5fd83dafce291024683b50dc89219333076',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '6460bd694f5e45fe9507eeb421d2d65fba4a4957',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '462d9819e5953e064e1dcdc04d3edc5fc6bc9431',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': '2176ec8c5f5d2272161277ab96fe5b8f7633113e',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '8b039cdeca40fdc4863dc15f7d5e2baa84f90e10',
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
