# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '963588074b26326ff0426c8953c1235213309bdb',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': '206eb6afeb290c16184960a9d519b6c3e1349726',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '3786ee89d584f5ba46f31dc5253e6dfaa222e5c1',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'c0fa1efc876e2113fbbb0785c512051dfaacfa07',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': 'e2e53a724677f6eba8ff0ce1ccb64ee321785cbd',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': 'b7947fe2d51e416666525c4d43a6e4398bb9f8a9',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'af3abdf3ec68a517e407c05f259cdadfd2b5cfe2',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': '4e246c56ec5afb5ad66b9b04374d39ac04675c8e',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '1ee7afc65286fe36a7e880acae5405b5eaedf3f4',
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
