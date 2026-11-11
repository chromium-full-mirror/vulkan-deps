# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': 'b2e081c8eb3ee90415908b7637c1ae429994bddc',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': 'f3353fc09adcf02a6524e2101c0ee2c17d91a140',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '6efe5ae6b7c6ad29da3f2cc3f164b9c3d72b78b1',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '251c437ef506157c139f77f5525c02223bc78868',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '88487f687f3100ebe1d3559a8a34d971ee85b977',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': 'e16c2af035b53a7c80cc66c3a3b0c24fa6768237',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '1d3fbab1ff5abce9f3eb9f3e7fcf66f455ae4475',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': '5a873d3b75d38ef6a0833589ce3603d63f3f6a9c',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '46917cddb2a29aaacca26b3be6dc5e7d79e795b6',
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
