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
  'vulkan_headers_revision': '8a1e5840e7833a90b79c3fddb639f57c3772a641',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': 'b77d86a9e8cabec1b202fb1d724db67eade3836f',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '2a288f8284243645a8a50fe5f4c53209fdbd7905',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': '3e303cbe2bb165887c94d96498eef33b4309b5bd',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '9d42028ac8d006aa3fe37b21ea029013598434b0',
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
