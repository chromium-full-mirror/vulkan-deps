# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '4cf9d467c7c57679a0846b61a3d3b8d55574702c',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': 'b3d30057b15273ce449bb9952e15e65b3f556723',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'bab63ff679c41eb75fc67dac76e1dc44426101e1',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'b6a83226d75d15b1733d35ee9e26b8f895ecffcb',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '409c16be502e39fe70dd6fe2d9ad4842ef2c9a53',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': 'fb78607414e154c7a5c01b23177ba719c8a44909',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '084289634c9294355c87e7ad8e4ae8f7dfa29701',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': '4e246c56ec5afb5ad66b9b04374d39ac04675c8e',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '7a6329b34b1652acfd685941ed1f5735200cf522',
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
