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
  'lunarg_vulkantools_revision': 'aa2779fe2d5cab65a26358d2b5760184edf4add4',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '01e0577914a75a2569c846778c2f93aa8e6feddd',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'ef14ec7ca82c05a1e90f0f1b98c56e39739930fa',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': 'd1cd37e925510a167d4abef39340dbdea47d8989',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '50399a2c3011bea1941a977f5b90a241053af4bc',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '83cded838a1a6e2dadfda6b114c8e12135194718',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': 'a0543a68cca0de632c010724fad08fce0bc27679',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': 'b7cec35a0ca9d1197aeb85a00a5f426249e1e134',
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
