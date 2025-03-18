# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '8842cf92e3de290f275c46d55cbfe42b7d0775a6',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': 'd6ec71c7a4734af3e5c0d0fa809c57d7a9bb64de',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'd5ee9ed2bbe96756a781bffb19c51d62a468049a',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '36a3ef46e4e0272ce21ca4778244202099a130dc',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': 'd64e9e156ac818c19b722ca142230b68e3daafe3',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '54cbefd25dbcaeb2bb03da207afce6cad7fb5dd1',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '072c8124dc6721df9b9c47f48830319b3218227a',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': 'bc3a4d9fd9b46729651a3cec4f5226f6272b8684',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '633315e4ca760d0740573dfadc8d0d2dacd76b5d',
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
