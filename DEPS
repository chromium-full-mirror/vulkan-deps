# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': 'a9b9dc1e6be82ff83aa222c2d8d58068db4f9772',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': '8724104e20fe263b884c07d6b7533d6df0595206',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'b824a462d4256d720bebb40e78b9eb8f78bbb305',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'fb7471844504abb16b732dc4fc0837119a32ec24',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '39c50d7bf094853a1f9a2e8a7e3377d425ae0c6a',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '8b5249c247d21edc96cac28d166005038fe8e286',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '0a1fb7e8cb346f69862e4f12c1d7b09d23e2f84c',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': '3249c4eedf225c113c6a341b0dc08d3681716895',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': 'b1bf1caabfaef4eebc15ee00c6ee952eaeeb12d6',
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
