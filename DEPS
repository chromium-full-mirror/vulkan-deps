# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': 'dcf1aaa6fd7dc2081f17aa0a4f1590a76473d961',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': '8c09437d1680411c45ad630bf02a9ae108d71376',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '869266ad9e6050197d87cf0a22aab59abf7ad008',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'a52828d672ab1622c308d0a6fc99630b79561609',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': 'f6a6f7ab165cedbfa2a7d0c93fe27a2d01ce09c8',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '1bf213b2a90181553fff35aeb6fa5c468dcfd35d',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '7c46da2b39036a80ce088576d5794bf39e667f56',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': '5f62a4c3c686d3d3d1b3973a4397dd4d4768f3ad',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '4be46d82a4d24c0f78c7e39dfa623ceef29c202e',
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
