# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '9d764997360b202d2ba7aaad9a401e57d8df56b3',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': '79c24a5c8015281f33f8ffd307b9d10bc1f17b4a',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '01e0577914a75a2569c846778c2f93aa8e6feddd',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'bc980018ddfff551a988760e3d09803b2f1889f3',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': 'd1cd37e925510a167d4abef39340dbdea47d8989',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': 'f4b28d2855e587bb3c287a75c23d8cc251d9111f',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'c9ed944bb39a564dbf15d0bdda63cc145018ed84',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': 'a0543a68cca0de632c010724fad08fce0bc27679',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '34ea98ed3035293274f66d3590429da857ea2d2c',
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
