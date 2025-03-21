# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': 'e57f993cff981c8c3ffd38967e030f04d13781a9',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': '80814c3ed544804f19d9fc4bd9992c6e3b59482a',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '0e710677989b4326ac974fd80c5308191ed80965',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'db06346b03b5e01b8af58b842fe4b068f47f9e46',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '78c359741d855213e8685278eb81bb62599f8e56',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '54cbefd25dbcaeb2bb03da207afce6cad7fb5dd1',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '072c8124dc6721df9b9c47f48830319b3218227a',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': 'bc3a4d9fd9b46729651a3cec4f5226f6272b8684',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '4159f13cc2bd82a60c3b72d3389e1a00b594b81e',
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
