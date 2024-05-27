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
  'spirv_headers_revision': '49a1fceb9b1d087f3c25ad5ec077bb0e46231297',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '77c40bece1b8b441eee432fc9d74efbf985f777f',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '5677bafb820e476441e9e1f745371b72133407d3',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': 'd3d530c90dd6549bcfc7cfaedd3ff85fe8ff04a2',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'd67a9d3a394e11c1c4c0f480124f5b7925cb1b4d',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': '8bc338928b5c92489d953e049018eab2359d437a',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': 'ee4ac8ea868cf33da30281e25380415c3434523f',
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
