# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '68a17eb72182d3dcfac834eed3512ea205eac9d1',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': '413b7630fa6005667c83133ee7475e14309d1d93',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '2acb319af38d43be3ea76bfabf3998e5281d8d12',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '581279dedd59d8353322fc2d61be07ccdcad0f13',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': 'e3c37e6e184a232e10b01dff5a065ce48c047f88',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': 'db0d129d43bda308328f91b15a5409161fbd50b7',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '345af476e583366352e014ee8e43fc5ddf421ab9',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': '1b07de9a3a174b853833f7f87a824f20604266b9',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '1dac3fd8b30cc42befff774f12e57334445e9f1b',
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
