# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': 'b83b2462ae7199c1560c68a710fb373bc2f75f86',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': 'dcbd02e0e7a6ed2892af97bfeb3c9871c53fd7de',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'f31ca173eff866369e54d35e53375fadbabd58f4',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'cb38b2342beedde25bcff582dc3528a135cf6e67',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '49f1a381e2aec33ef32adf4a377b5a39ec016ec4',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '09a024d4e422f8e603412f582d76c2051ef51cfc',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '39a19dccf79d28951516c3c7c9f1ee4a606fb733',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': '50af38b6cd43afb1462f9ad26b8d015382d11a3d',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': 'e21ca37295d9615b78b7bed9efa152df9c4e40ad',
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
