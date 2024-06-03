# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '2b19bf7e1bc0b60cf2fe9d33e5ba6b37dfc1cc83',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'ff2afc3afc48dff4eec2a10f0212402a80708e38',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '95681dc42f92af0bd8d881f81f3bd3035cbb6497',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '192d051db3382e213f8bd9d8048fc9eaa78ed6ab',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '21effda93a239cc4d726b37738c27fdc3e20ec3e',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'd67a9d3a394e11c1c4c0f480124f5b7925cb1b4d',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': '6bc92daa125da7aed037b46513845ebc67bc96e6',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': 'ea735538dc886f35e463d6e0c502e129366f7ab4',
}

deps = {
  'glslang/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/glslang@{glslang_revision}',
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
