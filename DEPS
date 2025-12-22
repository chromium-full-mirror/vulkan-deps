# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '9a8c5fd1f485736d29ef470d1b6981c5de73a365',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': '031011bb2a278a972b0b457e15cb077ae98434cf',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '0a7f626a6ae86284a413d105b47a6fb413bf6c92',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '91ac969ed599bfd0697a5b88cfae550318a04392',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '450bd2232225d6c7728a4108055ac2e37cef6475',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '7a07afe04ad134d4eabe25f62720177f60ed6627',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '1343cb3a9ca1a52fc6575f1471cf2b656bf1050a',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': '9a3f4105c16bde4e2717eeab0fcc5a49236f7294',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': 'c06f130a5dfbba4b9fd541d89be6ccadc42871bc',
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
