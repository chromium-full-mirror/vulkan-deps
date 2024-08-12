# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '7c4d91e7819a1d27213aa3499953d54ae1a00e8f',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': 'a12be94856baf210bb7ae9457dbdf907148caa0a',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'f013f08e4455bcc1f0eed8e3dd5e2009682656d9',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '87fcbaf1bc8346469e178711eff27cfd20aa1960',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '595c8d4794410a4e64b98dc58d27c0310d7ea2fd',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': 'faeb5882c7faf3e683ebb1d9d7dbf9bc337b8fa6',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '7d5cdf62e4f2935425faab1270fe1c9a401fa664',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': '45b881573538f8e481cb6e1d811a9076be6920c1',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': 'be6b3dcec385060966e4381ee145cbf1835a4e6a',
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
